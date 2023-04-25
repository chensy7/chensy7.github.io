---
layout: page
permalink: /publications/
title: publications
description: publications
years: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<!-- {% for y in page.years %} -->
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f papers --group_by type %}
<!-- {% endfor %} -->

</div>
