---
layout: project
type: project
image: ../images/fang.png
title: Fang-Defang-UI
permalink: projects/fang-defang-ui
# All dates must be YYYY-MM-DD format!
date: 2021-10-28
labels:
  - Python
  - APIs
  - Open Source
summary: A Python GUI for fanging or defanging artifacts.
---

<center>
<div class="github-card" data-github="jdoescyber/fang_defang_ui" data-width="400" data-height="153" data-theme="default"></div>
<script src="//cdn.jsdelivr.net/github-cards/latest/widget.js"></script>
</center>

[fang_defang_ui](https://github.com/jdoescyber/fang_defang_ui) is a very simple Python GUI which allows an analyst to quickly fang or defang artifacts.

This project was born out of a desire to handle IOCs that are collected with different formats: some threat reports will be fanged, others will be defanged. Instead of `CTRL + F`ing my way through it, I decided to write a Python script. The script originally took a file path (a text file, typically) and then converted the contents of that file.

Shortly thereafter, a fellow analyst asked if I had a GUI for it. I didn't, so I built one. This is the GUI that exists today.

❗ - To be very clear, this project was made possible by the folks that maintain the `ioc_fanger` Python module.

<div class="ui rounded images">
  <img class="ui image" src="../images/fang_defang_example.png">
</div>
