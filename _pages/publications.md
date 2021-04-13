---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Citations link directly to manuscript PDFs.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}




## Disclaimer:
Links to these papers are provided for your personal, non-commercial use. Research journals require a source of revenue to offset the true costs of publishing and archiving scientific research. The official record is always the paper available from their controlled webpages.

