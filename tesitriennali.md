---
layout: page
title: Tesi triennali
permalink: /tesitriennali/
---

## Elenco tesi triennali svolte 

<ul>
{% for tesi in site.tesitriennali %}
  <li><a href="{{site.baseurl}}{{ tesitriennali.url }}">{{ course.course-name }} presso {{ course.institution }}</a></li>
{% endfor %}
</ul>
