---
title: Publications
layout: page
---

# Publications

## Journal Articles
{% for pub in site.data.publications.journals %}
- {{ pub.authors | replace: "Your Name", "**Your Name**" }}. "[{{ pub.title }}]({{ pub.link }})". *{{ pub.journal }}*, {{ pub.year }}.
{% endfor %}

## Conference Papers
{% for pub in site.data.publications.conferences %}
- {{ pub.authors | replace: "Your Name", "**Your Name**" }}. "[{{ pub.title }}]({{ pub.link }})". *{{ pub.conference }}*, {{ pub.year }}.
{% endfor %}
