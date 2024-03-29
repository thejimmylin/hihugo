---
title: Ubuntu DB ODBC issues
date: 2022-05-29T02:11:05+08:00
draft: true
author: Jimmy Lin
---

# Ubuntu DB ODBC issues

ODBC could be annoying, these article list out some ODBC issues I got.

1. Using Ubuntu 20.04 to connect to a MSSQL:

   ```bash
   sudo su
   curl https://packages.microsoft.com/keys/microsoft.asc | apt-key add -
   curl https://packages.microsoft.com/config/ubuntu/19.10/prod.list > /etc/apt/sources.list.d/mssql-release.list
   exit
   sudo apt-get update
   sudo ACCEPT_EULA=Y apt-get install -y msodbcsql17
   sudo ACCEPT_EULA=Y apt-get install -y mssql-tools
   sudo apt-get install unixodbc-dev
   ```

2. For Windows 10:

   ```bash
   https://docs.microsoft.com/en-us/sql/connect/odbc/download-odbc-driver-for-sql-server
   ```

Note:

ODBC issue is so annoying so I don't want to test all of these situations well. Please use these commands carefully and do the some Google research before using them. Or just backup your data in case there are some unexpected error.
