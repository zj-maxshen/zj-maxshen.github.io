---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

211. Zeng, Z., Dai, H., Zhang, D. J., Zhang, H., Zhang, R., Xu, Z., & Shen, Z. J. M. (2023). The impact of social nudges on user-generated content for social network platforms. Management Science, 69(9), 5189-5208.

210. Qi, M., Shi, Y., Qi, Y., Ma, C., Yuan, R., Wu, D., & Shen, Z. J. M. (2023). A practical end-to-end inventory management model with deep learning. Management Science, 69(2), 759-773.


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


