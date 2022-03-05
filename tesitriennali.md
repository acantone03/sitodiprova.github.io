---
layout: page
title: Tesi triennali
permalink: /tesitriennali/
---

## Elenco tesi triennali svolte 
stampa
<ul>
{% for tesi in site.tesitriennali %}
  ciao
  <li><a href="{{site.baseurl}}{{ tesitriennali.url }}">{{ tesitriennali.tesi-name }}</a></li>
{% endfor %}
</ul>
