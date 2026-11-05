---
layout: page
title: life
permalink: /life/
---

life updates and check-ins

<ul>
  {% for post in site.tags.life %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      — {{ post.date | date: "%d %B %Y" }}
    </li>
  {% endfor %}
</ul>
