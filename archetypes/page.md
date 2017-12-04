---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
draft: false
hero-img:
---

{{ partial "hero.html" . }}