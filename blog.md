---
title: 'Blog'
date: 2020-02-12T17:01:34+11:00
layout: 'page'
---

Index of posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

