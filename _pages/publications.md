---
layout: archive
title: ""
description: "Research publications and technical outputs by Anderson Sabogal in vacuum engineering, accelerator technology, fusion, safety, experimental systems and intelligent control."
permalink: /publications/
author_profile: true
---

# Publications & Research Outputs

My research and engineering work spans **vacuum systems, accelerator technology, fusion engineering, safety, experimental validation, controls and data-driven modelling**.

The list below combines peer-reviewed journal articles, conference papers, submitted manuscripts, preprints and selected technical research outputs. Where a public document is available, the original PDF or publication record is linked directly.

For the authoritative researcher record, see my [ORCID researcher profile](https://orcid.org/0000-0002-9911-9786).

{% assign publications_sorted = site.publications | sort: "date" | reverse %}
{% for post in publications_sorted %}
  {% include archive-single.html %}
{% endfor %}
