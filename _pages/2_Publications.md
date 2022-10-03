---
layout: page
permalink: /publications/
title: Publications
years: [2022]
nav: true

---
<!-- _pages/publications.md -->
<div class="publications">

<h2>Conferences<h2> 
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conferences -q @*[year={{y}}]* %}
{% endfor %}

