---
layout: archive
title: "Work Samples"
permalink: /samples/
author_profile: true

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: main.jpg
---
{% include base_path %}

Most of my work at Finch Therapeutics is confidential IP and cannot be published online. If you'd like to talk about it in a context that won't earn me a strongly worded letter from Legal, please [reach out.](/contact/)

{% for post in site.samples %}
  {% include archive-single.html type="grid"%}
{% endfor %}