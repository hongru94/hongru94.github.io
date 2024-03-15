---
layout: archive
# title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications

Game-theoretic modeling of pre-disaster relocation

- You can find the full list of my publications at [Google Scholar](https://scholar.google.com/citations?user=rBkH7h0AAAAJ&hl=en).
