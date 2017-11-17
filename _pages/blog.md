---
layout: archive
title: "Blog"
permalink: /blog/
---

<div class="grid__wrapper">
  {% for post in site.posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

<!-- <div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div> -->

<!-- {% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %} -->