---
layout: page
title: Hello Genomics World!
tagline: We are all in the matrix.
---
{% include JB/setup %}

TEST: This is a TODO list
--

This content is located in index.md

To-Do:

* Change layouts for page
* Change layouts for posts
* Change images to make the page look better
* post some content

This theme is still unfinished. You can change layouts in genomicslife/jekyllbootstrap
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
