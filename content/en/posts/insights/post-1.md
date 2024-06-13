---
title: Improving Templater  templates over time
draft: false
tags:
  - obsidian
  - IT/program/quartz
  - productivity
  - automation
aliases:
  - Improving Templater  templates over time
date: 2024-06-13
enab:
---
 Just a place where I want to store all of tips used to make this page a bit easier to manage

## Shared prompt value

It is possible to ask once for a prompt in a [Templater](https://github.com/SilentVoid13/Templater) plugin:

```
<%*

let title = await tp.system.prompt("Podaj tytuł")

-%>
---
title: <% title %>
// ..
aliases:
  - <% title %>
```
[Source](http://www.macdrifter.com/2021/08/obsidian-templater-fun.html)
 