---
layout: base.njk
title: Mis videojuegos favoritos.
---

# {{ title }}
En este blog hablare sobre mis videojuegos favoritos dividienlos en 3 categorias de genero que mas me gustan.

## Generos

### First Person Shooter

{% for videojuego in collections.FPS %}

- [{{videojuego.data.title}}]({{ videojuego.url | url }})

{% endfor %}

### Accion

{% for videojuego in collections.accion %}

- [{{videojuego.data.title}}]({{ videojuego.url | url }})

{% endfor %}

### RPG

{% for videojuego in collections.RPG %}

- [{{videojuego.data.title}}]({{ videojuego.url | url }})

{% endfor %}
