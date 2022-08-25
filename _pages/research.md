---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<br>

**Research interests**
My research focuses on financial communication and the perceptions of capital market participants.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
