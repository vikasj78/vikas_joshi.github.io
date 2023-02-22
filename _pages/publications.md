---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Below are some of my publications, a full list can be found at my Google Scholar link on the left.
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
