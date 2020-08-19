---
layout: home
title: "GTD"
permalink: /projects/GTD/
classes: wide
---

## BASH TOOLS

Find the differences in two directories

```
diff -rq dir1 dir2 | grep 'Only in dir2/'
```

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
