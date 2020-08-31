---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
My updated publication list can also be found at [PubMed](https://www.ncbi.nlm.nih.gov/myncbi/1TkD9bvoywa5v/bibliography/public/) and [ORCID](https://orcid.org/0000-0002-4198-3336).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
