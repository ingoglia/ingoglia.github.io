---
layout: page
title: blog
permalink: /blog/
---

Computers

<ul>
  {% for post in site.categories.computers %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

Philosophy

<ul>
  {% for post in site.categories.philosophy %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
