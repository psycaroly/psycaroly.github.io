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

<img src="https://github.com/psycaroly/psycaroly.github.io/blob/master/images/wordcloud.png?raw=true">

{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}
