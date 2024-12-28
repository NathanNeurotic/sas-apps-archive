---
title: In Game Reset (IGR)
subtitle: Return memcard pro to the boot card when OPL IGR is triggered
description: Return memcard pro to the boot card when OPL IGR is triggered
developer: JonathanDotCel
visit_project: https://github.com/JonathanDotCel/bootcard_igr
hide_hero: true
sysapps_code: SAL001-005
layout: sysappslist
image: https://i.postimg.cc/PrmwPHf5/mcethumb-Recovered-Recovered-copy.png
version: v0.1
features:
    - label: Compatible across all models
      icon: fa-user-check
    - label: Updated sometimes
      icon: fa-file-upload
    - label: Fairly popular
      icon: fa-chart-line
download: https://app.filen.io/#/d/1da94440-50c7-47ce-a9b4-15fd223b03af#2kqIHZ70G83uSv5Oq1CPzu9h1bKEteq7
rating: 5
---

An IGR (intergrated reset) binary, which will mount your default MCP2 boot card then restart the PS2.

You can use it 2 ways:

1: Use it as your `IGR.ELF` for OPL

OPL will launch it when you hit the IGR key combo, restart the MCP2, and then restart the PS2

2: Install it as a FMCB menu item

Scroll to it and hit `X` when FMCB starts to load your default boot card on the MCP2
