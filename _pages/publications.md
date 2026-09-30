---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here is a list of selected publications. You can find the full list of publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
