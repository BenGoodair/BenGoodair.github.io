---
layout: archive
title: "Publications"
header:
  image: /warmingstripes2.jpg
permalink: /publications/
author_profile: true
---

<h2>Journal Articles</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


<h2>Reports, commentaries and blogs</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'academic' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
