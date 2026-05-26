---
layout: page
title: blog
permalink: /blog/
---
## Reflexiones y Artículos
Aquí podrás conocer mis pensamientos sobre ciertos temas:

{% for post in site.posts %}
  {% if post.categories contains 'blog' %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %b %Y" }}
  {% endif %}
{% endfor %}

*(More Coming soon — stay tuned)*
