---
layout: archive
title: "Certifications"
permalink: /posts/
author_profile: true
---

{% include base_path %}

{% for post in site.certifications %}
  {% include archive-single-certificate.html %}
{% endfor %}
