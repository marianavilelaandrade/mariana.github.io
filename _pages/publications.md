---
layout: archive
title: "Publications"
permalink: marianavilelaandrade.github.io/publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include 2009-10-01-paper-title-number-1.md %}
{% endfor %}
