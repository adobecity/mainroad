---
title: "{{ replace .TranslationBaseName '-' ' ' | title }}"
description: "new"
date: "{{ .Date }}"
thumbnail: "images/placeholder.png"
categories:
  - "new"
tags:
  - "new"
lead: "Example lead - highlighted near the title" # Lead text
comments: false # Enable Disqus comments for specific page
authorbox: true # Enable authorbox for specific page
pager: true # Enable pager navigation (prev/next) for specific page
toc: true # Enable Table of Contents for specific page
mathjax: true # Enable MathJax for specific page
sidebar: "right" # Enable sidebar (on the right side) per page
widgets: # Enable sidebar widgets in given order per page
  - "search"
  - "recent"
  - "categories"
  - "taglist"
---