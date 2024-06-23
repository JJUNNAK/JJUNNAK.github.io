---
title: "spring"
layout: archive
permalink: /spring
---

{% assign posts = site.categories.spring %}
{% for post in posts %} {% include archive-single.html tyoe=page.entries_layout %} {% endfor %}