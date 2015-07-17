---
layout: archive
title: "Group"
date: 2015-07-15
modified:
excerpt: "Current and former group members."
tags: []
image:
  feature:
  teaser: Default_400x250.jpg
---

<div class="tiles">
{% for post in site.categories.group %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->