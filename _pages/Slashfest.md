---
layout: archive
permalink: /slashfest/
title: "Devlog for Slashfest"
author_profile: false
header:
    image: "/images/bg.png"
---

{% for logs in site.logs %}
    {% include archive-single.html %}
{% endfor %}
