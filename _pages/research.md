---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/2023-bib.png"
---

I am an Assistant Professor in the field of bioinformatics currently working at Shandong University, China. My research has particularly focused on developing computational and experimental approaches to identify novel metabolic biomarkers in cancer and neurodegenerative disease. 

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" | reverse %}

{% for post in ordered_pages %}
  {% include archive-single.html type="list" %}
{% endfor %}
