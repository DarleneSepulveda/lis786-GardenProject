---
title: Shop
layout: page
permalink: /shop
---

{% for design in site.designs %}
<div class="column">
            <h4>{{ design.title }}</h4>
            <p><img src="{{design.product_image}}" alt="{{design.img_alt}}" width="200" height="200"> </p>
</div>
{% endfor %}