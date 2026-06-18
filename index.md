---
layout: home
lang: en
permalink: /
---
{% capture body %}
{% include index.md %}
{% endcapture %}
{{body | markdownify}}
