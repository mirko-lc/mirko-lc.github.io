---
layout: page
title: blog
permalink: /blog/
---














{% for post in site.posts %}
  {% if post.categories contains 'blog' %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %b %Y" }}
  {% endif %}
{% endfor %}
