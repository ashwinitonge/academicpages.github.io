---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Mentees’ names underlined. Asterisk indicates dual first-author position. Open access articles (<i class="ai ai-fw ai-open-access-square"></i>) are linked below; all other PDFs (<i class="fa fa-file-pdf-o" aria-hidden="true"> </i>) are provided for **personal use only.** Supplementary materials on GitHub (<i class="fa fa-github" aria-hidden="true"></i>) and OSF (<i class="ai ai-fw ai-osf"></i>) for each publication are linked below the citation.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
