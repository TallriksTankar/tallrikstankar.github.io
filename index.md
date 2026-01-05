---
layout: default
title: Welcome to My Food Blog
---

## Latest Recipes

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date_to_string }}
    </li>
  {% endfor %}
</ul>

---