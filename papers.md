---
title: Papers
permalink: /papers/
---

<ul>
{% for paper in site.data.papers %}
  <li>
      {{ paper.nombre }} (<i><a href="{{ paper.url }}">{{paper.editorial }}</a>
      </i>, {{ paper.ano }})
  </li>
{% endfor %}
</ul>
