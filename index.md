---
layout: default
title: Home
---

{% for p in site.posts %}
<hr>
<h3>{{p.title}}</h3>
<hr>
{{p.content}}
{% endfor %}
