---
layout: default
title: Proyectos
permalink: /proyectos/
---

<h1>Listado de Proyectos</h1>

<ul>
  {% for proyecto in site.proyectos %}
    <li>
      <h2><a href="{{ proyecto.url }}">{{ proyecto.nombre }}</a></h2>
    </li>
  {% endfor %}
</ul>
