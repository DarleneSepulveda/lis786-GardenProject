---
title: Shop
layout: page
permalink: /shop
---

### Recent Designs
{% for design in site.designs %}
#### {{ design.title }}
![design.alt](design.image)
{% endfor %}