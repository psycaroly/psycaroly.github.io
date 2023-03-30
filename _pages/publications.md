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

<img src="/images/wordcloud.png">

<small><i>This wordcloud was made with R and the <a href="https://cran.r-project.org/web/packages/wordcloud2/vignettes/wordcloud.html">wordcloud2</a> package by Lang (2023).<i>

{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}
