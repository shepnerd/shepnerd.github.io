---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=Xm2M8UwAAAAJ">my Google Scholar profile</a>.</u>

Selected Publications

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
