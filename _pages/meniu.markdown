---
layout: page
title: Meniu
permalink: /meniu/
is_main_page: true
---

<div class="menu">
  {% for item in site.data.menu %}
  <div class="category {{ item.id }}">
    <a href="{{ site.baseurl }}/{{ item.id }}" style="color: black;-webkit-tap-highlight-color: rgba(0,0,0,0);-webkit-tap-highlight-color: transparent;"><h2>{{ item.name }}</h2></a>
    
  </div>
  {% endfor %}
</div>
