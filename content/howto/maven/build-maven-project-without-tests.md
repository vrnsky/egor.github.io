---
title: Build Maven Project without tests
type: docs
sidebar:
  open: true
tags:
  - maven
next: know-what-dependency-do-you-have
comments: true
---

If you would like to run build of Maven project in concurrent mode you can use following command
```bash
mvn clean package -DskipTests
```
