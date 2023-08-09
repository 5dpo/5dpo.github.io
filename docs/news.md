---
layout: default
title: News
nav_order: 3
permalink: /news
---

# News

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
