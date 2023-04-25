---
layout: page
permalink: /publications/
title: publications
description: publications
types: ['conf', 'journal']
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.types %}
  <h2 class="type">{{y}}</h2>
  {% bibliography -f papers -q @*[type={{y}}]* %}
{% endfor %}

</div>