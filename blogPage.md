---
layout: page
title: blog
permalink: /blog/
---

<div class="layout">
<article class="card neumorphism-card-big" id="computers-blog" >
  <h1 class="title">Computers</h1>
  {% for post in site.categories.computers %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</article>
<article class="card neumorphism-card-big" id="philosophy-blog" >
  <h1 class="title">Philosophy</h1>
  {% for post in site.categories.philosophy %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</article>
</div>
