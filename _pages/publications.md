---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a complete list of my articles on <ins>[my Google Scholar profile](https://scholar.google.com/citations?user=v1bbB_YAAAAJ&hl=en)</ins>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
