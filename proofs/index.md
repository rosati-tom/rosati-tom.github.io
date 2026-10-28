---
title: AI proofs
layout: default
math: false
---

[← Home](/)

----

## AI proofs

Writeups of proofs produced by AI models. Each page states the model used
and whether I have checked the argument; unchecked proofs may contain errors.

{% assign proofs = site.pages | where_exp: "p", "p.dir != '/proofs/'" | where_exp: "p", "p.url contains '/proofs/'" | sort: "date" | reverse %}
{% for p in proofs %}
> [{{ p.title }}]({{ p.url }}), {{ p.date | date: "%-d %b %Y" }}{% if p.status %} <span class="proof-status">({{ p.status }})</span>{% endif %}.
{% endfor %}
{% if proofs.size == 0 %}
*Nothing here yet.*
{% endif %}

----
