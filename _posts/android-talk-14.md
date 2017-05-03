---
published: false
layout: post
comments: true
header-img: img/post/post_03.jpg
date: 2017-05-02T10:00:00.000Z
subtitle: Android Talk 14.
author: Alan Ortiz
author_pic: /img/team/Alan.jpg
bio: 'Estudiante Carrera de Informatica, Back-end, Organizer GDG Android Bolivia'
fb_user: null
tw_user: null
gp_user: null
gh_user: null
yt_user: null
ws_user: null
email: lizarraga.gux@gmail.com
title: 'FAB Buttons, ¿Que puedo hacer con ellos?'
---

# FAB buttons: ¿Que puedo hacer con ellos?

## ¿Que es un FAB button y para que sirve?
[material.io](https://material.io/guidelines/components/buttons-floating-action-button.html)

>A floating action button represents the primary action in an application.

>A floating action button is used for a promoted action.

>Shaped like a circled icon floating above the UI, it changes color upon focus and lifts upon selection. When pressed, it may contain more related actions.

Segun la guia de material design, un boton de accion flotante o FAB Button es un boton que representa la accion primaria en una aplicacion, tambien es usado para promover una accion principal.

Su forma es un circulo flotante encima de la Interfaz,  y cambia de color al enfocar y se eleva al seleccionar. Cuando es presionado, puede contener mas acciones relacionadas.

Entonces en resumen, un FAB es un boton muy importante dentro de una aplicacion que resalta su accion principal por la cual fue creada la app, ahora tambien la guia nos da algunas recomendaciones de que cosas debemos y no debemos hacer a la hora de implementar FABs en nuestras aplicaciones, para que de esa manera estemos en armonia con los lineamientos del material design en cuanto a una mejor UI y UX que haran que nuestra aplicacion llegue a gustar a nuestros usuarios por su elegancia y confort. 

##Recomendaciones
**Un FAB por pantalla**

https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQseVdNVnYtc0loblk/patterns_actions_fab_placement10.png

Una de las cosas importantes a la hora de implementar un FAB es no usar mas de un FAB en la activity principal, esto se debe a que como indica la deficion "representa la acción primaria" si colocamos mas FAB al mismo tiempo en la pantalla, el usuario quedara muy confundido de cual de ellos accionar para la acción principal que quiere realizar.

https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B1PhAWhtrRTrTWlzUzcwS3hpU3c/patterns_actions_fab_placement8.png


**La Forma de un FAB**

https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B1PhAWhtrRTrekhFaTJmbDhSM0U/patterns_actions_fab_qualities6.png

La forma de un FAB debe ser "un circulo de color plano con un icono sencillo", cuando se cambia la forma o se le da un volumen o bien llega a perderse y no resaltar en la pantalla o bien llega a superponerse demasiado y distraer al usuario del resto de los componentes distribuidos en la pantalla.

https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B1PhAWhtrRTrOHBsN0xtTFJ5aEE/patterns_actions_fab_qualities5.png

**Toolbar**
https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsbjUzX1ZOei1uazA/patterns_actions_fab_actions12.png

Si queremos mostrar acciones importantes relacionadas en nuestra aplicacion es mejor convertir nuestro FAB en un toolbar, pero la guia nos dice que los item que esten en la toolbar tienen que tener una relacion una con la otra y con la aplicacion y su proposito.

https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6Okdz75tqQsZHRMSzRFTXhoMnM/patterns_actions_fab_actions10.png 

**FAB como menu con mas opciones**

https://storage.googleapis.com/material-design/publish/material_v_11/assets/0B6GnvA6rl3tYVFJuZXhVU3lMRnM/components_fab_flyouts_dont4.png

Otra manera de mostrar acciones que el usuario puede usar de manera mas rapida es al momento de presionar el FAB que esta despliegue mas opciones, pero tienen que ser al menos tres opciones mas y nunca poner una opcion para desplegar mas opciones pues el usuario tardaria mas tratando de buscar lo que quiere desplegando una y otra ves las opciones, al final desintalara su aplicacion.

**El unico limite es su imaginacion**

Aunque parezca que un FAB no haga mucho, en realidad puede darle al usuario una interaccion con su aplicacion de tal manera que llegue a disfrutarlo e incluso llegue a estar entre sus app preferidas por la elegancia en su disenio, su simplicidad y accesibilidad en cuanto a su interaccion.

Para terminar material design has sido un conjunto de consejos que estan respaldados por varios documentos, entre las cuales estan estudios y encuestas en cuanto a como les gustaria que sean las aplicaciones para un usuario final, y FAB ha tenido en este ultimo tiempo un gran impacto entre los usuarios y segun el escritor, marca la diferencia entre un app de antigua de una que esta proyectada a las nuevas tendencias.

Para mas informacion en cuanto a los FAB visitar el siguiente enlace [material FAB](https://material.io/guidelines/components/buttons-floating-action-button.html#buttons-floating-action-button-large-screens) 
