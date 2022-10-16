---
layout: default
title: "blog"
---

<!-- add pages list view here -->

<ul class="no-bull">
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%d %m %Y" }} | <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
