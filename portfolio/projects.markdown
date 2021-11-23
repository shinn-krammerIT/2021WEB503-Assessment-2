---
layout: page
title: Projects
permalink: /projects/
---

<container style="display: flex; flex-wrap: wrap; gap: 25px;">
{% for post in site.categories.projects %}
    <div style="padding: 5%; border-style: solid; border-radius: 25px;"><a href="{{ post.url }}">{{ post.title }}</a><br>{{ post.description }}</div>
{% endfor %}
</container>