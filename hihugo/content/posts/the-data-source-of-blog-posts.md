---
title: The data source of blog posts
date: 2022-05-29T02:11:05+08:00
draft: true
author: Jimmy Lin
---

# The data source of blog posts

Here are some data source I consider to use in my blog posts.

## TL;DR

| Type           | Support content     | Stored as | Online update | Github stars |
| -------------- | ------------------- | --------- | ------------- | ------------ |
| MDX            | Anything            | Markdown  | No            | 11.5k        |
| mdx-bundler    | Almost anything     | Markdown  | Yes           | 0.7k         |
| react-markdown | Plain markdown only | Markdown  | Yes           | 7.7k         |
| Quill          | Many but limited    | HTML      | Yes           | 30.9k        |

## What is MDX?

According to [https://mdxjs.com/](https://mdxjs.com/):

> MDX is an authorable format that lets you seamlessly write JSX in your Markdown documents.

That is to say, with MDX, you can write something like this:

```jsx
# Hello, **world**!

Below is an example of JSX embedded in Markdown.

<div style={{ padding: '20px', backgroundColor: 'tomato' }}>
  <h3>This is JSX</h3>
</div>
```
