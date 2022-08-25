---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

> It's **not** about Debits and Credits

My research focuses on financial communication and the perceptions of capital market participants. To this end, I use machine learning methods and natural language processing tools to harvest novel data from corporate disclosures and other sources (e.g., social media and news outlets).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
