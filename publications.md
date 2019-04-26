---
layout: default
title: Publications
permalink: /publications/
---

<ul>
{% for item in site.data.publications %}
  <li><i>{{item.title}}</i></li>
{% endfor %}
</ul>
