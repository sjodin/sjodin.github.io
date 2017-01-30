---
layout: page
title: Favorites
links:
  Bright Eyes: qwWp6vnAF50
  Rilo Kiley - Portions for foxes: qtNV3pOqcjI
  Basket: ysFZ3Uqudww
  Ending of Six Feet Under: 3difXqlpwVc
  Thåström - Om Black Jim: V9LBHr92Rr4
---
{% for link in page.links %}
{{ link[0] }}
<iframe width="560" height="315" src="https://www.youtube.com/embed/{{ link[1] }}" frameborder="0" allowfullscreen></iframe>
{% endfor %}