---
layout: home
title: "GTD"
permalink: /projects/GTD/
classes: wide
---




<ul>
{% for post in posts %}
  {% if post.tags contains 'gtd' %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="date">{{ post.date | date: "%B %-d, %Y"  }}</span>
  </li>
  {% endif %}
{% endfor %}
</ul>