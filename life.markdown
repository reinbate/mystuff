---
layout: page
title: life
permalink: /life/

<ul>
  {% for post in site.tags.life %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      — {{ post.date | date: "%d %B %Y" }}
    </li>
  {% endfor %}
</ul>
---

life updates and check-ins
