---
layout: archive
title: "Submitted Papers"
permalink: /submitted/
author_profile: true
---

lated research.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.submitted reversed %}
  {% include archive-single.html %}
{% endfor %}