---
layout: page
title: Menu
permalink: /meniu2/
---

<div class="menu">
  {% for item in site.data.menu %}
  <div class="category">
    <h2>{{ item }}</h2>
  </div>
  {% endfor %}
</div>
