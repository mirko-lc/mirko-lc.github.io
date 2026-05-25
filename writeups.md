---
layout: page
title: writeups
permalink: /writeups/
---
## CTF Writeups & Security Research
Aquí iré publicando mis writeups de CTFs, máquinas de HackTheBox, TryHackMe, y otros retos.

{% for post in site.posts %}
  {% if post.categories contains 'writeups' %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %b %Y" }}
  {% endif %}
{% endfor %}




*(More Coming soon — stay tuned)*





