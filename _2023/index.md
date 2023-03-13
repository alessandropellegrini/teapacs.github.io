---
layout: default
title: "TeaPACS 2023"
---

{% include banner.html picture="miami.jpg" %}<!-- @IGNORE PREVIOUS: link -->

---

{% for coll in site.collections %}{% if coll.label == page.collection %}{% assign edition = coll %}{% endif %}{% endfor %}
{%- assign year = page.collection -%}

The {{ year }} International Workshop on Teaching Performance Analysis of Computer Systems (TeaPACS) will take place at {{ edition.location }} on {{ edition.dates }} in {{ edition.venue }}.

## Important Deadlines

{% include_relative _important_dates.md %}
