---
layout: archive
permalink: /projects/
title: "Project Posts by Tags"
author_profile: true
header:
  image: "/images/programming.jpeg"
---

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}
