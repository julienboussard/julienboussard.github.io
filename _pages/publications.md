---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

Here is a list of selected publications. You can find the full list of publications on [my Google Scholar profile]({{ site.author.googlescholar }}){:target="_blank"}


{% include base_path %}

{% assign papers = site.publications | where_exp: "p", "p.pubtype != 'thesis'" | reverse %}
{% assign theses = site.publications | where: "pubtype", "thesis" | reverse %}

# Conferences and Journals
{: .pub-section}

{% for post in papers %}
  {% include publication-card.html %}
{% endfor %}

---

# PhD Thesis
{: .pub-section}

{% for post in theses %}
  {% include publication-card.html %}
{% endfor %}
