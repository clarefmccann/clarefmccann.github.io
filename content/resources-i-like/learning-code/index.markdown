---
author:
categories:
draft: false
excerpt: helpful resources for learning and troubleshooting different types of code
layout: single-sidebar
location:
subtitle:
title: learning code
date: "2022-12-08"
---

<script src="{{< blogdown/postref >}}index_files/clipboard/clipboard.min.js"></script>
<link href="{{< blogdown/postref >}}index_files/xaringanExtra-clipboard/xaringanExtra-clipboard.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/xaringanExtra-clipboard/xaringanExtra-clipboard.js"></script>
<script>window.xaringanExtraClipboard(null, {"button":"<i class=\"fa fa-clipboard\"><\/i> Copy Code","success":"<i class=\"fa fa-check\" style=\"color: #90BE6D\"><\/i> Copied!","error":"Press Ctrl+C to Copy"})</script>
<link href="{{< blogdown/postref >}}index_files/font-awesome/css/all.css" rel="stylesheet" />
<link href="{{< blogdown/postref >}}index_files/font-awesome/css/v4-shims.css" rel="stylesheet" />

## learn by doing!

>tips:
  > if you usually clean your data in a certain language or platform, try using a new one!

  > [stackoverflow](https://stackoverflow.com/)

  > interactive tutorials! (e.g., [datacamp](https://www.datacamp.com/?irclickid=1u8RaNyBuxyNRS2w-Vw7PXGtUkAxuMS90QtpU80&irgwc=1&utm_medium=affiliate&utm_source=impact&utm_campaign=000000_1-2334778_2-mix_3-all_4-na_5-na_6-na_7-mp_8-affl-ip_9-na_10-bau_11-Linkbux&utm_content=ONLINE_TRACKING_LINK))

  > become really good at googling - copy + paste the important part of your errors!

  > if you find the answer, challenge yourself to understand why that way works and your way doesn't

{{< panelset class="greetings" >}}
{{< panel name="R">}}
  - [R for Data Science](https://r4ds.had.co.nz/)
  - [R Cheatsheets](https://support--rstudio-com.netlify.app/resources/cheatsheets/)
  - [Swirl](https://swirlstats.com/students.html)

  #### getting scientific notation for your output?

  ```r
      options(scipen=999)
  ```

  #### fav package manager + some fav packages
```r
pacman::p_load("dplyr", "ggplot2", "psych", install = TRUE)
```

  #### want to knitr a nice html from your markdown? ----> [bookdown](https://bookdown.org/yihui/rmarkdown/html-document.html)

{{< panel name="GitHub" >}}
  GitHub is extremely useful for version control!!!! You create repositories for your projects which are basically like folders but they are collaborative (e.g., run one line of code to clone a repo, make edits, push it back to github so someone else can implement the edits) and track everything that's ever been done.

  [Create an account](https://github.com/)
  [GitHub Documentation - getting started!](https://docs.github.com/en/get-started/quickstart/hello-world)

  I highly recommend generating [access tokens](https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) and [ssh keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) for ease of use. You can interact with git on the [command line](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) and manage your project with just a couple of lines of code.

  One thing I live by - before you start making any edits in a repo, always run:
  ```r
  git status
  ```

{{< panel name="Command Line" >}}

You can customize your terminal to your liking -- see [charles dobson's post](https://medium.com/@charlesdobson/how-to-customize-your-macos-terminal-7cce5823006e) for a step-by-step tutorial 

KEY COMMANDS:

> `cd` stands for change directory. it's how you will move in and out of different directories on your machine.

> `ls` stands for list. you can run this in any directory and it will output its contents.</br>
  ---> note: i like running `ls -al` which will give you a lot more information (e.g., permissions, date last modified, file size, etc.)

> MORE TO COME (this page is a work in progress)

{{< panel name="Python" >}}

I'm also learning `python` right now so this will serve more as a notes section. Coming soon.
