---
layout: archive
title: "Working Papers"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
 #ou can also find my articles on <u><a href="{{author.google schoolar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
