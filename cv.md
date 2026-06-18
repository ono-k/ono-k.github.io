---
layout: page
title: CV
lang: en
permalink: /cv/
---
{% capture body %}
{% include cv.md %}
{% endcapture %}
{{body | markdownify}}
