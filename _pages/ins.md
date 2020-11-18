---
layout: page
permalink: /ins/
title: ins
description: Instagram
nav: false
---

{% jekyllgram 6 %}
  <a href="{{ photo.link }}" title="{{ photo.caption.text }}">
    <img src="{{ photo.images.thumbnail.url }}" title="{{ photo.caption.text }}" />
  </a>
{% endjekyllgram %}
