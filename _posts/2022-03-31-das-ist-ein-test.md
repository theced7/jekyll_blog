---
layout: post
title:  "Das ist ein Test!"
date:   2022-03-31 19:14:27 +0200
---

# Test!

Das ist ein **Test-Post** um *Markdown* und **Jekyll** auszuprobieren.

Das ist ein 2. Absatz.

- Das ist eine Liste
- das ist ein 2. Item.

Was macht das?
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>