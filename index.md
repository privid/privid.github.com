---
layout: page
title: Test
tagline: Supporting tagline
---
{% include JB/setup %}


<ul class="posts" style="list-style:none; list-image:none;">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

