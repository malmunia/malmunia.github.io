---
layout: page
permalink: /publications/
title: research
description: 
years: [2022,2021,2019,2018]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>