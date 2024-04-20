---
layout: default
title: Games
---

<h1>Listado de Juegos</h1>

<ul>
{% for game in site.games %}
  <li><a href="{{ game.url }}">{{ game.title }}</a></li>
{% endfor %}
</ul>
