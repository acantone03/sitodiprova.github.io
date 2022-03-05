---
layout: page
title: Tesi triennali
permalink: /tesitriennali/
---

## Elenco tesi triennali svolte 

<ul>
{% for tesi in site.tesitriennali %}
  <li><a href="{{site.baseurl}}{{ tesitriennali.url }}">{{ tesitriennali.tesi-name }}</a></li>
{% endfor %}
</ul>
