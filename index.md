---
layout: page
title: Kelmer Perez, Neutral Good, Level 1 Web Developer, Level 4 Nerd
tagline: Supporting tagline
---
{% include JB/setup %}

#### Welcome to my web site.  The purpose of this site is to show projects I have worked on, projects I'm currently workign on, and interesting technology I want to explore.



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

