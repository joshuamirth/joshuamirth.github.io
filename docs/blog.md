---
layout: page
title: Blog
permalink: /blog/
use_math: true
---

Recent blog posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
