---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}


My research interests are in area of cyber-physical and energy systems, from the perspective of machine learning, optimization, and control. During my Ph.D. studies, I developed algorithms for controlling and optimizing resources in energy systems and discovered fundamental, societal-scale insights in data-driven control systems. 

Here is a list of the current and previous research projects that I have worked on.

{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

