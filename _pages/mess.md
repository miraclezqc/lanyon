---
layout: archive
title: "Mess"
permalink: /mess/
author_profile: true
---

## Maybe introduce some toolkits in this space.

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% assign flag = true %}
  {% for tag in post.tags %}
    {% if tag == "tool" %}
      {% assign flag = false %}
    {% endif %}
  {% endfor %}
  {% if flag == false %}
    {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
