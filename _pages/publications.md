---
permalink: /publications/
title: "Publications"
excerpt: "List of academic publications."
author_profile: true
redirect_from: 
  - 
---

{% include base_path %}

## Peer-Reviewed 
{% if site.author.researchgate and site.author.googlescholar and site.author.orcid %}
  You can also find my articles on: <a href="{{ site.author.googlescholar }}" target="_blank">Google Scholar</a>  &#124; <a href="{{ site.author.researchgate }}" target="_blank">ResearchGate</a> &#124;  <a href="{{ site.author.orcid }}" target="_blank">ORCID</a>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

