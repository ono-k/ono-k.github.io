---
layout: home
lang: ja
permalink: /ja/
---
{% capture body %}
{% include index.md %}
{% endcapture %}
{{body | markdownify}}
