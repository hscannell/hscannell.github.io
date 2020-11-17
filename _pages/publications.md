---
permalink: /publications/
title: "Publications"
excerpt: "List of academic publications."
author_profile: true
redirect_from: 
  - 
---

{% include base_path %}

<H3 align="center"> Research Manifesto </H3>
<p align="center"><img src="/images/rainbow.jpeg" width="100%"></p>
<p align="center"> <i>I believe in <b>quality</b>, not quantity; <b>reproducibility</b>, not one-and-done; <b>open-source</b>, not proprietary; <b>collaboration</b>, not isolation; <b>inclusivity</b>, not segregation; <b>diversity</b>, not homogenization.</i> </p> </br>


## Journal Articles
{% if site.author.researchgate and site.author.googlescholar and site.author.orcid %}
  You can also find my articles on: <a href="{{ site.author.researchgate }}" target="_blank">ResearchGate</a> &#124; <a href="{{ site.author.googlescholar }}" target="_blank">Google Scholar</a> &#124; <a href="{{ site.author.orcid }}" target="_blank">ORCID</a>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


