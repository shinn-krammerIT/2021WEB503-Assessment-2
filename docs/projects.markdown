---
layout: page
title: Projects
permalink: /projects/
---

{% for post in site.categories.projects %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

