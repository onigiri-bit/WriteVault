---
title: <% await tp.system.prompt("标题（默认取文件名）", tp.file.title, true) %>
date: <% tp.date.now("YYYY-MM-DD") %>
draft: true
tags: []
summary: "<% await tp.system.prompt("一句话摘要（显示在文章列表页）", "", true) %>"
hideSummary: false
---


