---
layout: project
type: project
image: images/acrotholus.png
title: Acrotholus - Validate IOCs/IOAs
permalink: projects/acrotholus
# All dates must be YYYY-MM-DD format!
date: 2021-10-28
labels:
  - Python
  - APIs
  - Threat Intelligence
  - Open Source
summary: A Python script that takes domains, IPs, and hashes, then checks for threat reputation against free APIs, preferring authentication-less APIs.
---

[Acrotholus](https://github.com/jdoescyber/Acrotholus), named for the [dinosaur who lived in the late Cretaceous](https://en.wikipedia.org/wiki/Acrotholus), is a series of Python scripts that aims to speed up validation of IOCs/IOAs by checking them against free APIs. There is a slight preference on authentication-less APIs (such as Alienvault OTX), but keys are supported in a YML file.
