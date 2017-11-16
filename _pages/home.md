---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/mm-home-page-feature.jpg
  cta_label: ""
  cta_url: ""
  caption:
excerpt: 'Be Hypnotic and Paranoid with us'
intro:
  - excerpt: 'Get notified when I add new stuff &nbsp; [<i class="fa fa-twitter"></i> @aquabubu1731](https://twitter.com/aquabubu1731){: .btn .btn--twitter} [<i class="fa fa-paypal"></i> Tip Me](https://www.paypal.me/payaquabubu){: .btn .btn--primary}'
---

{% include feature_row id="intro" type="center" %}

<div class="feature__wrapper">
  <h1>Tech Blog</h1>  
  <div class="grid__wrapper">
    {% for post in site.recipes %}
      {% include archive-single.html type="grid" %}
    {% endfor %}
  </div>
</div>

<div class="feature__wrapper">
  <h1>Life Blog</h1>
  <div class="grid__wrapper">
    {% for post in site.portfolio %}
      {% include archive-single.html type="grid" %}
    {% endfor %}
  </div>
</div>
