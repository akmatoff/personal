---
date: '{{ .Date | dateFormat .Site.Params.dateFormat }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---
