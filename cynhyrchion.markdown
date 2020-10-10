---
title: Cynhyrchion
date: 2020-10-08 09:51:00 Z
layout: page
---

<ul>
  {% for cynhyrchion in site.cynhyrchion %}
    <li>
      <a href="{{ product.url }}">{{ cynhyrchion.title }}</a>
<p>{{ cynhyrchion.short }}</p>
    </li>
  {% endfor %}
</ul>