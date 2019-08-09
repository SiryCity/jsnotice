---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
url: "posts/{{.File.BaseFileName}}"
tags: ['JavaScript',]
---

