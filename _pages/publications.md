---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
  <div class="wordwrap">Selected publications</div>
  <div class="wordwrap"><strong>2024</strong></div>
  <div class="wordwrap">Huang, W., Li, C. & Rivera-Monroy, V.H. Cold fronts control multiscale spatiotemporal hydroperiod patterns in a man-made subtropical coastal delta (Wax Lake Region, Louisiana USA). Ocean Dynamics 74, 355–372 (2024). https://doi.org/10.1007/s10236-024-01608-9</div>
  <div class="wordwrap">Huang, W., Ye, F., Zhang, Y., Du, J., Park, K., Yu, H.C., and Wang, Z. 2024b. Hydrodynamic responses of estuarine bays along the Texas-Louisiana coast during Hurricane Harvey. Ocean Modelling 187, 102302.</div>
  <div class="wordwrap">Li, C.; Huang, W.; Chen, C.; Boswell, K.M.; Wu, R. Modes of Weather System-Induced Flows through an Arctic Lagoon. J. Mar. Sci. Eng. 2024, 12, 767. https://doi.org/10.3390/jmse12050767</div>
  <div class="wordwrap"><strong>2023</strong></div>
  <div class="wordwrap">Huang, W., Y.J. Zhang, Z. Liu, H.C. Yu, Y. Liu, S. Lamont, Y. Zhang, F. Hirpa, T. Li, B. Baker, W. Zhang, S. Patel, and N. Mori. Simulation of Compound flooding in Japan using a nation-wide model. Natural Hazards. https://doi.org/10.1007/s11069-023-05962-7</div>
  <div class="wordwrap"><strong>2022</strong></div>
  <div class="wordwrap">Huang, W., Y.J. Zhang, F. Ye, Z. Wang, S. Moghimi, E. Myers, and H.C. Yu, 2022, Tidal Simulation Revisited, Ocean Dynamics, 1-19. https://doi.org/10.1007/s10236-022-01498-9</div>
  <div class="wordwrap"><strong>2021</strong></div>
  <div class="wordwrap">Huang, W., Ye, F., Zhang, Y., Park, K., Du, J., Moghimi, S., Myers, E., Pe'eri, S., Calzada, J.R., Yu, H.C., Nunez, K., and Liu, Z. 2021, Compounding factors for extreme flooding around Galveston Bay during Hurricane Harvey, Ocean Modelling 158, 101735. https://doi.org/10.1016/j.ocemod.2020.101735</div>
  <div class="wordwrap">Ye, F., Huang, W., Zhang, Y. J., Moghimi, S., Myers, E., Pe’eri, S., and Yu, H.-C.: A cross-scale study for compound flooding processes during Hurricane Florence, Nat. Hazards Earth Syst. Sci. 21(6), 1703-1719. https://doi.org/10.5194/nhess-21-1703-2021</div>
  <div class="wordwrap"><strong>2020</strong></div>
  <div class="wordwrap">Huang, W., C. Li, J. White, S. Bargu, B. Milan, and S. Bentley, 2020. Numerical Experiments on variation of freshwater plume from Mississippi River diversion in Lake Pontchartrain estuary, Journal of Geophysical Research: Oceans,125(2), C2019JC015282, https://doi.org/10.1029/2019JC015282.</div>
  <div class="wordwrap">Huang, W., and C. Li, 2020. Contrasting Hydrodynamic Responses to Atmospheric Systems with Different Scales: Impact of Cold Fronts vs. that of a Hurricane. Journal of Marine Systems and Engineering 8(12), 979. https://doi.org/10.3390/jmse8120979</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
