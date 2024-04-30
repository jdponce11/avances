---
layout: post
title:  "Decisiones sobre el blog y el alcance del proyecto"
date:   2024-04-30 00:01:02 -0600
categories: jekyll update
---

Me costó decidir qué herramienta para blogs utilizar. Al final opté por Jekyll con hosting en github pages, por la facilidad y lo gratis, para enfocarme totalmente en actualizar los avances del proyecto. 

# ¿Qué proyecto?

La idea del proyecto nace de la necesidad de tener una dieta balanceada, sin tener que calcular manualmente cada semana los días que necesito consumir ciertas comidas con nutrientes específicos, como vitaminas A, D, B12, calcio, hierro, ácido fólico, etc. 

Cabe mencionar que no pretendo hacer una guía nutricional, sino una herramienta que va de la mano del libro *"Guía a la alimentación vegana para Guatemala y Centroamérica"* de Attilio Altieri. De tal manera que el programa es una forma más fácil de interpretar y poner en práctica los tips y recetas del libro. 

En una sección del libro, éste tiene varias tablas de cómo distribuir las comidas con ciertos nutrientes durante una semana. Por ejemplo: 

### Vitamina C
Mínimo: 4-5 veces por semana
```table
| **Alimento** | **Porción** |
|--------------|-------------|
| Frutos cítricos (naranja, limón, lima, mandarina) | 2 unidades |
| Mango | 2 unidades |
| Papaya, piña, melón | la mitad de una papaya, piña o melón |
| Bledo, espinaca, verdolaga: hojas crudas o apenas salteadas | Medio manojo crudo o 1 taza medida después de la cocción |
| Brócolis | 1 taza |
```
La idea es cargar estas tablas con requerimientos semanales y las recetas a bases de datos, para que al presionar un botón, sea generado un plan de comidas semanal, cuyos ingredientes cumplen con los requisitos de nutrientes para una dieta balanceada.

# Requerimientos funcionales del proyecto

- Botón que al ser presionado, se muestre una tabla de la semana con recetas, que son links apuntando hacia la página de la receta.
    - Botón
    - Tabla de plan semanal con links.
    - Páginas para cada receta. 
    - Detalle de ingredientes por receta. 
    - Detalle de preparación por receta.

# Opciones de stacks y tecnologías a usar

Luego de investigar y darme cuenta de la dificultad de desarrollar una app móvil, he decidido que la herramienta será una aplicación web. De esa manera se puede abrir en cualquier dispositivo y el desarrollo se hace más sencillo. Para el frontend usaré React, y para el backend aún estoy revisando opciones, en específico estoy revisando si hacerlo con Node.js, Express y MongoDB. Una de las siguientes tareas es revisar si las opciones son compatibles con Heroku, ya que me llama la atención como servicoi para desplegar la aplicación. 
También quiero contenerizar mi aplicación en Docker, para familiarizarme con el proceso y que aporte valor al resultado final. 

# Metodología de desarrollo

Al ser un proyecto personal, no creo conveniente poner fechas límite para ir alcanzando logros clave, sino que iré a mi propio ritmo. Puede ser valioso investigar sobre la metodología Agile y ver si aporta algún valor a mi flujo personal. 

# Nota final

Quiero recalcar que este es un proyecto orientado a mi aprendizaje personal, por lo que mucho de lo que redacte en este blog puede ser información errónea, la cual espero ir corrigiendo conforme voy aprendiendo.

