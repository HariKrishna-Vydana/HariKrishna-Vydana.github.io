---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}


{% if author.googlescholar %}
  You can find my articles on: <u><a href="{{author.googlescholar}}">Google Scholar</a>.</u>
{% endif %}

<!-- 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
