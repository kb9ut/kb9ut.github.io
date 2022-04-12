---
title: "日記がてら猫の記録"
---

<ul>
  {% for post in site.posts %}
  <li>
    {{post.date | date: "%F" }}:<a href="{{site.github.url}}{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
