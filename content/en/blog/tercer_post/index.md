---
title: "Pruebas de sintaxis"
date: 2022-10-02T09:06:05-03:00
author: ProfeNomada
description: "Probando la sintaxis de markdown en hugo"
tags: ["blog", "posteo", "hugo"]
thumbnail: /blog/tercer_post/img/tercer_post.jpg
---

En este posteo voy a probar algunas de las formas de sintaxis que proveen hugo y el markdown juntos

## Vamos a hacer una tabla

| Nombre | Gustos | Peso | hobbies |
|--------|--------|------|---------|
| Juanito| Whiskas|4,5kg | correr como loco y bufandear |
| Pampa  | Excellent | 5,5kg| dormir y enojarse con palomas |

El renderizado de la tabla es excelente, hay que darle uso para los posteos.

## Shortcode para hacer un cuadro de código
{{< highlight html >}}
Esto deberia ser resaltado porque es html
<h1>prueba de Titulo</h1>
<p>prueba de parrafo</p>
Aunque se puede escribir cualquier tipo de texto según parece

{{< /highlight >}}