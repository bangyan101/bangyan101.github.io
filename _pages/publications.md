---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Selected publications I am a primary author on are highlighted.

<style style="text/css"> .hoverTable{ width:85%; border-collapse:collapse; border: 0px; } .hoverTable td{ padding:7px; border:#4e95f4 0px solid; } /* Define the default color for all the table rows */ .hoverTable tr{} /* Define the hover highlight color for the table row */ .hoverTable tr:hover { background-color: #f7f7f7; } </style> {% for post in site.publications reversed %} {% include publication_subdir.html %} {% endfor %}
