---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

Here is a list of selected publications. You can find the full list of publications on [my Google Scholar profile](site.author.googlescholar){:target="_blank"}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include publication-card.html %}
{% endfor %}
