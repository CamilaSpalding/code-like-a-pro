# Trucos de código

## Hacer codigo más rápido

### Truco 1: Crear una etiqueta padre con elementos hijos dentro

Para indicar la etiqueta a crear, escribir el nombre de la misma.

    nav

----
Para agregarle una clase a la etiqueta se debe escribir pegado .nombre-de-la-clase.

    nav.nav-bar

----
Para agregarle un id a la etiqueta se debe escribir pegado #nombre-del-id.

    nav.nav-bar#navigatio-bar

----
Para sumarle etiquetas hijo a la etiqueta padre se debe indicar que se cierra la etiqueta usando el signo ">".

    nav.nav-bar#navigation-bar>

----
Al igual que el primer paso, para seguir agregando etiquetas uno debe escribir el nombre de la etiqueta deseada, seguir con la clase o id si es necesario, si se quiere terminar ahi, se debe presionar "enter/return" sin el signo ">". Sino, volver a reperir el signo ">" y repetir los pasos.

    nav.nav-bar#navigation-bar>ul.menu-list>li.list-item

----
Para multimplcar una misma etiqueta -se puede o no incluir clases o id- se debe escribir seguido a la etiqueta *numero_de_repeticiones(en el caso de haber clases o id, escribirlo seguido de estos).

    nav.nav-bar#navigation-bar>ul.menu-list>li.list-item*4

----
Si se quieren agregar etiquetas diferentes dentro de una etiqueta padre se debe escribir el signo + para concatenar las distintas etiquetas que se quieren crear.

    nav.nav-bar#navigation-bar>ul.menu-list>li.list-item*4>span+button

----

### Truco 2: Crear una etiqueta padre con elementos hijos dentro

