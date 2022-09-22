---
band: "Band Name"
title: "{{ replace .Name "-" " " | title }}"
cover: "/images/releases/cover.jpg"
year: {{ now.Format "2006" }}
cat: "none"
format: "ep|lp|cd|mc"
date: {{ .Date }}
---
