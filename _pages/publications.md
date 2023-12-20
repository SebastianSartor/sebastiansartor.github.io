---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Publications
====== -->
Please refer to my [Google Scholar page](https://scholar.google.com/citations?user=qrTsOTYAAAAJ&hl=en) to make sure to have the latest updates included.

Papers submitted for peer-review
======


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
