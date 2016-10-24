---
layout: page
title: "Important Cat Gifs!"
---

{% for cat in site.data.catgifs %}

### {{ cat.title }}

![{{cat.title}}]({{ cat.img }})

{% endfor %}
