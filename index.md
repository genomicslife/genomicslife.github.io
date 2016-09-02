---
layout: page
title: Genomics Life
tagline: Ramblings about Genomics and all related science!
---
{% include JB/setup %}

Posts every week or every other week or whenever there are datasets of interest!

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
