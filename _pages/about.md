---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## News
<style style="text/css"> .news{font-size:0.75em;} </style>
{% include news.html %}


## Publications
<style style="text/css"> .hoverTable{ width:85%; border-collapse:collapse; border: 0px; } .hoverTable td{ padding:7px; border:#4e95f4 0px solid; } /* Define the default color for all the table rows */ .hoverTable tr{ background: #ffffff; } /* Define the hover highlight color for the table row */ .hoverTable tr:hover { background-color: #f7f7f7; } </style> {% for post in site.publications reversed %} {% include publications.html %} {% endfor %}
