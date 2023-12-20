---
layout: archive
title: "Academic Publications"
permalink: /publications/
author_profile: true
---

<!-- Publications
====== -->
Please refer to my [Google Scholar](https://scholar.google.com/citations?user=qrTsOTYAAAAJ&hl=en) page to make sure to have the latest updates included.

Papers submitted for peer-review
======

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
