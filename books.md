---
layout: page
title: Book Reviews
permalink: /books/
---

# 📚 My Book Reviews

Here are the books I've been reading and my thoughts on them.

<ul>
  {% for post in site.categories.books %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> 
      <small>({{ post.date | date: "%B %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>
