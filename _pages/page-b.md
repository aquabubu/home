---
layout: archive
title: "Page B"
permalink: /page-b/
date: 2011-06-23T18:39:14+00:00
---

(lorem ipsum)

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
