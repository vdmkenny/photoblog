---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
description: ""  # write-up for the entire roll
draft: true
cover: ""
film:       ""     # e.g. "Portra 400"
camera:     ""     # e.g. "Canon AE-1"
lens:       ""     # e.g. "50mm f/1.8"
# no image param; Hugo will pick up all JPGs in the bundle
---

{{< rollgallery >}}
