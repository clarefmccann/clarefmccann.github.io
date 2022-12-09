---
author:
categories:
date: "2022-12-08"
draft: false
excerpt: helpful resources for learning and troubleshooting different types of code
layout: single
location: Online
subtitle:
title: learning code
---

### learn by doing!
- there's no better way to learn than having to...
    - tips:
        - if you usually clean your data in a certain language or platform, try using a new one to add dimension to your skillset.
        - stackoverflow <3
        - interactive tutorials! (e.g.,[datacamp](https://www.datacamp.com/?irclickid=1u8RaNyBuxyNRS2w-Vw7PXGtUkAxuMS90QtpU80&irgwc=1&utm_medium=affiliate&utm_source=impact&utm_campaign=000000_1-2334778_2-mix_3-all_4-na_5-na_6-na_7-mp_8-affl-ip_9-na_10-bau_11-Linkbux&utm_content=ONLINE_TRACKING_LINK))
        - commit to completing a project using a specific language
        - become really good at googling - copy + paste your errors!
          - if you find the answer, challenge yourself to understand why that way works and your way doesn't

{{< panelset class="greetings" >}}
{{< panel name="R">}}
  - [R for Data Science](https://r4ds.had.co.nz/)
  - [R Cheatsheets](https://support--rstudio-com.netlify.app/resources/cheatsheets/)
  - [Swirl](https://swirlstats.com/students.html)

  #### getting scientific notation for your output?
      > options(scipen=999)
  #### fav package manager + some fav packages
      > pacman::p_load("dplyr", "ggplot2", "psych", install = TRUE)
  #### want to knitr a nice html from your markdown? ----> [bookdown](https://bookdown.org/yihui/rmarkdown/html-document.html)

{{< panel name="GitHub" >}}
  GitHub is extremely useful for version control!!!! You create repositories for your projects which are basically like folders but they are collaborative (e.g., run one line of code to clone a repo, make edits, push it back to github so someone else can implement the edits) and track everything that's ever been done.

  [Create an account](https://github.com/)
  [GitHub Documentation - getting started!](https://docs.github.com/en/get-started/quickstart/hello-world)

  I highly recommend generating [access tokens](https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) and [ssh keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) for ease of use. You can interact with git on the [command line](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) and manage your project with just a couple of lines of code. 

{{< panel name="Command Line" >}}
{{< panel name="Python" >}}
