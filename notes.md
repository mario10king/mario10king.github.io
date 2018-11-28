---
layout: page
title: Notes
permalink: /notes
---
## Why I take notes?

{% for item in site.data.notes %}
  See my notes on [{{item.name}}.](./{{item.link}})
{% endfor %}
