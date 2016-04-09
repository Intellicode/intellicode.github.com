---
layout: index
title: Notes by Tom Hastjarjanto
---

<ul class="posts">
  {% for post in site.posts %}
    <li><span><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
