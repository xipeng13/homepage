---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Hello world
![PUB1](https://xipeng13.github.io/homepage/images/PUBLICATION-1.jpg)
![PUB2](https://xipeng13.github.io/homepage/images/PUBLICATION-2.jpg)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
