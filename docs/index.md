---
layout: rapport
order: 1
---

# Labs - web

<a href="/rapport_global/rapport"> Guide des labs </a> 

## Consultation par sections

<ul>
  {% for package in site.data.lab_info.packages %}
    <li> <a href="/{{ package.name }}/rapport"> {{ package.titre }} </a> </li>
  {% endfor %}
</ul>
