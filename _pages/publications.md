---
layout: archive
title: "PUBLICATIONS"
permalink: /publications/
author_profile: true
---
\
You can find the articles on my [Google Scholar](https://scholar.google.com/citations?user=LcEe3_EAAAAJ&hl=en) profile.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
