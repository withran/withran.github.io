---
layout: page
title: Personal Blog
permalink: /blog/
---

# ✍️ Daily Thoughts & Learning

A space for me to document my journey and daily reflections.

<ul>
  {% for post in site.categories.blog %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> 
      <small>({{ post.date | date: "%B %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>
