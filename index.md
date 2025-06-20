---
title: Welcome to my blog
---

My name is shreyash, and I will write a blog on statistics-related things. Stay tuned!!


<ul>
  {% for item in site.showcase %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
      {% if item.description %}
        - {{ item.description }}
      {% endif %}
    </li>
  {% endfor %}
</ul>
