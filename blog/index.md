---
layout: default
title: Tjian's blog list
---

<h1>{{ page.title }}</h1>
<ul class="posts">
    {% for post in site.posts %}
    <li>{{ post.date | date_to_string }}<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>