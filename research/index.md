---
layout: archive
title: "Research"
date: 2015-07-15
modified:
excerpt: "Research projects."
tags: []
image:
  feature: waterfall_panorama.jpg
  teaser: ChiFia_400x250.jpg
---


<div class="tiles">
{% for post in site.categories.research %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->