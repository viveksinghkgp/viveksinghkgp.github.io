---
title: Publications
layout: page
---
{% for pub in site.data.publications.journals %}
- **{{ pub.authors }}**. "[{{ pub.title }}]({{ pub.link }})". *{{ pub.journal }}*, {{ pub.year }}.
{% endfor %}
