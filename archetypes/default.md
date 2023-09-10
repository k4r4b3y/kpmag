---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
author: "{{ .Site.Params.author }}"
---
