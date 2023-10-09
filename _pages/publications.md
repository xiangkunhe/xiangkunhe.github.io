---
layout: archive
title: " "
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{[author.googlescholar](https://scholar.google.com/citations?hl=zh-CN&user=xpyS8ksAAAAJ&view_op=list_works&sortby=pubdate)}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
