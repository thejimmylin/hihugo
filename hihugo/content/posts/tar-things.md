---
title: Tar things
date: 2022-05-29T02:11:05+08:00
draft: true
author: Jimmy Lin
---

# Tar things

1. To see the content

   ```bash
   tar -tf your_file.tar.gz
   ```

2. To extract .tar

   ```bash
   tar -xvf your_file.tar
   ```

3. Compress .tar

   ```bash
   tar -cvf your_file.tar /the/file/or/directory/path
   ```

4. To extract .tar.gz

   ```bash
   tar -zxvf your_file.tar.gz
   ```

5. To compress as .tar.gz

   ```bash
   tar -zcvf your_file.tar.gz /the/file/or/directory/path
   ```

Tips:

```bash
-t check
-f file_name
-z use gzip
-c/-x compress/extract
```
