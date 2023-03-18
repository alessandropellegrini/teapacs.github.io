---
layout: default
title: "The Second International Workshop on<br/>T e a P A C S"
---

{% include banner.html picture="orlando.jpg" %}<!-- @IGNORE PREVIOUS: link -->

---

{% for coll in site.collections %}{% if coll.label == page.collection %}{% assign edition = coll %}{% endif %}{% endfor %}
{%- assign year = page.collection -%}

UNDER CONSTRUCTION

The workshop on Teaching Performance Analysis of Computer Systems (T e a P A C S) was conceived on the 50th anniversary of SIGMETRICS, with an objective to take stock of performance modeling analysis as a discipline. It was held in 2021 and co-located with the IFIP Performance conference in Milano, Italy.

The need to open the discussion on this topic comes, on the one hand, from the obvious consideration that, since the formation of ACM SIGMETRICS and IFIP TC 7 (which includes WG 7.3 Computer System Modeling), computing systems have changed drastically. The growing complexity of systems, services, and their relative context makes it more urgent and critical to model and analyse the performance and behaviour of systems. On the other hand, the teaching of performance modeling has faced cutbacks as budgets are squeezed and student interests shift.

The workshop aims to stimulate discussion on how the community should respond to this challenge. Consequently, the chosen format is to have invited speakers and discussions open to all participants.
