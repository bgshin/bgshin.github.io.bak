---
layout: page
permalink: /publications/
title: publications
description: [Google Scholar](https://scholar.google.com/citations?user=j9nUzZAAAAAJ&hl=en).
# years: [2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008, 2007]
years: [2019, 2017, 2012, 2011, 2010, 2008, 2007]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
