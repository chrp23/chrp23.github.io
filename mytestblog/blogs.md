---
layout: post
title: "We're testing out new Blog Page"
categories: Oranges
permalink: /blogs/

---

<ol>
  {% for post in site.posts %}
    {%- if post.categories == "Oranges" -%}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
    {%- endif -%}
  {% endfor %}
</ol> 

