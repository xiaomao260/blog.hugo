---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
lastmod: 
draft: true
tags: [ "", "", "" , "", "", "", ""]
categories: [ "日记"]
DropCap: true
slug: {{ substr (md5 (printf "%s%s" .Date (replace .TranslationBaseName "-" " " | title))) 4 8 }}

---
