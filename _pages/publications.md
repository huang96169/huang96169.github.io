---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
  <div class="wordwrap">Huang, W., Li, C. & Rivera-Monroy, V.H. Cold fronts control multiscale spatiotemporal hydroperiod patterns in a man-made subtropical coastal delta (Wax Lake Region, Louisiana USA). Ocean Dynamics 74, 355–372 (2024). https://doi.org/10.1007/s10236-024-01608-9</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
