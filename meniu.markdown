---
layout: page
title: Meniu
permalink: /meniu/
is_main_page: true
---

<div class="menu">
  {% for item in site.data.menu %}
  <div class="category">
    <h2>{{ item }}</h2>
  </div>
  {% endfor %}
</div>
