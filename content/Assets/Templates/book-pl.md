<%*
let title = await tp.system.prompt("Podaj tytuł")
-%>
---
title: <% title %>
draft: false
tags: 
 - Typ/Recenzja
 - Książka
aliases:
  - <% title %>
date: <% tp.date.now("YYYY-MM-DD") %>
---
 
