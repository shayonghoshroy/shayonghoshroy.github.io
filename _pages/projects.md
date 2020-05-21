---
layout: archive
permalink: /projects/
title: "Checkout how I created some of my projects!"
author_profile: true
header:
  image: "/images/banner.jpg"
---

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}
