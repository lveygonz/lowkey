---
title: lowkey
---

[Post](_posts/2025-06-21-Eso.md)

# Courses
[- Biologia i Geologia 4 (ESO)](https://github.com/lveygonz/biogeo4)

# Scripts
- Apps Script

# Últimos posts

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%d %b %Y" }}</li>
  {% endfor %}
</ul>
