---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- 
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
 -->

<ol reversed>{% for post in site.publications %}
  {% assign year = post.date | date: "%Y" %}
  {% capture current_year %}{{ year }}{% endcapture %}
  {% if current_year != previous_year %}
    {% if forloop.index != 1 %}</li>{% endif %}
    <li><h2>{{ year }}</h2>
  {% endif %}
  {% include archive-single-cv.html %}
  {% assign previous_year = year %}
{% endfor %}</li></ol>