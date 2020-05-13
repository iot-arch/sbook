---
author: Michael Henderson
date: '2020-09-28T00:00:00.000Z'
prev: /tutorials/automated-deployments
next: /tutorials/github-pages-blog
title: Creating a New Theme
weight: 10
linktitle: Creating a New Theme
menu:
  main:
    parent: Tutorials
---

# Introduction

We'll start with creating a new site with a very basic template. Then we'll add in a few pages and posts. With small variations on that, you will be able to create many different types of web sites.

In this tutorial, commands that you enter will start with the "$" prompt. The output will follow. Lines that start with "\#" are comments that I've added to explain a point. When I show updates to a file, the ":wq" on the last line means to save the file.

Here's an example:

```text
## this is a comment
$ echo this is a command
this is a command

## edit the file
$ vi foo.md
+++
date = "2020-09-28"
title = "creating a new theme"
+++

bah and humbug
:wq

## show it
$ cat foo.md
+++
date = "2020-09-28"
title = "creating a new theme"
+++

bah and humbug
$
```

