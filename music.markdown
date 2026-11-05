---
layout: page
title: music
permalink: /music/
---

<ul>
  {% for post in site.tags.music %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      — {{ post.date | date: "%d %B %Y" }}
    </li>
  {% endfor %}
</ul>
