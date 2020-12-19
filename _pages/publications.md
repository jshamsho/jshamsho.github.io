---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Coming soon
**Shamshoian, J.**, Senturk, D., Jeste, S., Telesca, D. "Bayesian Covariance Regression in Functional Data."

Watson, G. L., Xiong, D., Zhang, L., Zoller, J. A., **Shamshoian, J.**, Sundin, P., Bufford, T., Rimoin, A. W., Suchard, M. A., Ramirez, C. M. "Fusing a Bayesian Case Velocity Model with Random Forest for Predicting COVID-19 in the U.S."

### Completed research
Li, Q., **Shamshoian, J.**, Senturk, D., Sugar, C., Jeste, S., DiStefano, C., Telesca, D. (2020). "Region-Referenced Spectral Power Dynamics of EEG Signals: A Hierarchical Modeling Approach." *Ann. Appl. Stat.* 14(4).

**Shamshoian, J.**, Senturk, D., Jeste, S., Telesca, D. (2020). "Bayesian Analysis of Longitudinal and Multidimensional Functional Data." *Biostatistics*, kxaa041.

Xiong, D., Zhang, L., Watson, G. L., Sundin, P., Bufford, T., Zoller, J. A., **Shamshoian, J.**, Suchard, M. A., Ramirez, C. M. (2020). "Pseudo-likelihood based logistic regression for estimating COVID-19 infection and case fatality rates by gender, race, and age in California." *Epidemics*. 33.

Paquin, D., Sacco, D., **Shamshoian, J.** (2015). "An analysis of strategic treatment interruptions during imatinib treatment of chronic myelogenous leukemia with imatinib-resistant mutations." *Mathematical Biosciences*. 262.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
