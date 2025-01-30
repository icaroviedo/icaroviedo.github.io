---
permalink: /archive
layout: page
title: Archivu
---

Entraes anteriores

<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
