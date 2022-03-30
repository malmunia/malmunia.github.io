---
layout: page
permalink: /research/
title: Research
description: 
years: [accepted,2021,2020,2019,2018,2012,2010]
nav: true
---

#### Publications
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>



#### Working Papers / In progress

* “Information, Fiscal Capacity and Tax Compliance: An Experimental Evaluation”
with David J. Henning, [Justine Knebelmann](https://sites.google.com/view/justine-knebelmann/home) and [Lin Tian](https://lin-tian.github.io/)
  
* “The Value-Added Tax: Theory and Practice”
  with [Anne Brockmeyer](https://www.annebrockmeyer.com/), [Giulia Mascagni](https://www.giuliamascagni.net/), [Vedanth Nair](https://ifs.org.uk/people/profile/5001) and [Mazhar Waseem](https://mazharwaseem.com/)

#### Old Working Papers 

* [“Points to Save Lives: Traffic Enforcement Policies and Road Fatalities”](/assets/pdf/points_to_save_lives_oct17.pdf)
  with [Gonzalo Gaete](http://gonzalogaete.weebly.com/)