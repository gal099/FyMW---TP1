__Matería: Frontend y Maquetado Web__
===
`Alumno`: Juan Baez
----
***
**Trabajo Práctico #2**
---------
>Utilizando como base el HTML commiteado en el Trabajo Práctico anterior, implementar las siguientes consignas:

1. Crear una nueva rama en el repositorio, con el nombre 'trabajo-practico-2'.
2. Por medio de la hoja de estilos existente, y sin alterar el HTML, conseguir: 

    1- Que todos los textos tengan una tipogarfía 'serif' a elección.

    2- Que el tamaño de las tipografías para todo elemento del documento sea por defecto 16px.

    3- Que los elementos h1..h6 tengan una tipografía no negrita.

    4- Que todos los links del elemento nav del documento dejen de tener subrayado, y que sus letras sean todas mayúsculas.

    5- Que los textos de párrafo tengan una alineación justificada, y un alto de línea del doble del tamaño de la tipografía base. Expresar el tamaño en una unidad relativa.

    6- Usando una misma regla, que todos los elementos \<article> que son hijos del elemento cuyo id es "post" y el primer elemento \<section> hijo de \<footer>, tengan bordes punteados gris claro (color hex #CCCCCC), de 2px de grosor. (Tip: revisar conceptos de agrupamiento, anidamiento y pseudo-clases de selectores)

    7- Que todos los input y textarea dentro del \<form> hijo de \<footer>, tomen un color de fondo "green" cuando se posiciona el cursor en ellos.

    8- Que el elemento \<nav> esté fijo en la parte superior de la pantalla, y se mantenga visible en esa posición al hacer scroll (Tip: revisar conceptos de posicionamiento CSS)

    9- Forzar que los elementos \<li> del \<nav> del punto anterior, funcionen como cajas, con un padding de 10px por lo menos, y que se muestren uno al lado de otro (tip: usando la propiedad "display" o la propiedad "float").

    10- Con una nueva regla, declarar que todos los elementos \<article> que son hijos del elemento cuyo id es "post" (los mismos mencionados en el punto 2.6), ocupen la mitad del espacio horizontal disponible, que tengan un padding horizontal con un valor del 1% del ancho del viewport, y que se comporten de manera "inline" entre sí.

    11- Lograr que los elementos del punto anterior incluyan los bordes y paddings dentro de su ancho declarado, en lugar de que sumen sus espesores al tamaño final de la caja.

    12- Con una regla única, hacer que el \<form> tenga un ancho del 50% de su contenedor, y que quede centrado en su espacio horizontal. (Tip: revisar si el form es de tipo inline o block, y aplicar reglas de centrado de acuerdo a ello).

3. Commitear los cambios: puede ser un commit por cada sub/item del punto 2, o un commit único. Pushear la rama al repositorio remoto, y crear en el mismo un pull request a la rama "master" o "main". El entregable de esta actividad será la URL del pull request.

***
***

**Trabajo práctico #1**
------------------

>Para este trabajo, utilizaremos los conceptos vistos en clase, y el repositorio público que comentamos en la clase 2.  

**Consigna**
----


`Paso 1 (pre-requisitos)`

Crear un repositorio local con Git para alojar los archivos del proyecto. Incluir un archivo README.md con una breve descripción acerca del proyecto.
Crear un repositorio remoto, de acceso público, en alguna de las siguientes plataformas: Github (https://github.com/), GitLab (https://gitlab.com/) o Bitbucket (https://bitbucket.org/).

`Paso 2`

Ir a [el sitio donde está el template que vamos a usar] https://html5up.net/uploads/demos/massively/, y copiar el código fuente de la página.
En nuestro proyecto local, crear un archivo `index.html` en el repo y pegar el html en él.
Hacer un nuevo commit en la rama master con un mensaje, como por ejemplo: "Agrega index.html como codigo de referencia."
Utilizar el comando `git push` para subir los cambios al repo remoto.

`Paso 3`

Crear un archivo `styles.css`
Agregar una regla CSS para el `body` del documento y cambiar el `background-color`.
Linkear el archivo en el `head` de nuestro `index.html` utilizando el tag `link`.
Ir al browser y corroborar que el color de toda la página cambia de color. También podemos corroborar en el tab Network de las herramientas del browser que nuestro sitio está haciendo un request extra para incluir el archivo `styles.css` y que el código (status code) es `200`. Tomar una captura de pantalla.
Efectuar un commit en la rama master que incluya estos nuevos cambios con un mensaje descriptivo como "Incluye styles.css con color de fondo para el body."
Utilizar `git push` para subir los cambios al repositorio remoto.
