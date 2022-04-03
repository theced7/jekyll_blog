---
layout: post
title:  "Das ist ein neuer Test!"
date:   2022-04-01 00:00:27 +0200
---

## Das ist ein 2. Test.

Wie der wohl aussschauen mag?

Das ist ein Bild: ![Bild](/assets/img/1.png)

## Das ist ein Test für das plugin `timeago`

{% assign date = '2020-04-13T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}