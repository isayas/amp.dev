---
$title: Curso de Introducción
$order: 2
leveled: true
---

[filter level="beginner"]
## ¿Para quién es este curso?

Este curso esta diseñado para desarrolladores web iniciales y desarrolladores que buscan mejorar el rendimiento de los sitios web. A lo largo de este y los siguientes cursos, podrás:

- Conocer las diferencias entre las páginas AMP y los sitios web tradicionales (“vanilla”).

- Construir un proyecto de ejemplo de forma incremental usando componentes reales AMP y mejores prácticas.

- Aprender estrategias para construir sitios web modernos.

## Prerequisitos

Para aprovechar al máximo estos cursos, debes tener conocimientos básicos de HTML y CSS. Es suficiente con que reconozcas código HTML y CSS, y poder agregar pequeñas adiciones y modificaciones como se indica en los ejercicios. Ten en cuenta que la enseñanza de estos conceptos está más allá del alcance de este curso. Si es necesario, puedes encontrar un repaso en HTML [aqui](https://developer.mozilla.org/en-US/docs/Web/HTML) and y CSS [aqui](https://developer.mozilla.org/en-US/docs/Web/CSS).

## Sigue el Código con Glitch

Para completar el código de los ejemplos incluidos en estos cursos, podremos usar <a href="https://glitch.com/" target="_blank">Glitch</a>. Glitch es un editor de código en línea que te permite crear y visualizar sitios web sin la necesidad de instalar algo en tu computadora. Te permite crear un servidor, todo dentro de la interfaz de Glitch.

El ambiente del editor de código Glitch luce así:

{{ image('/static/img/courses/beginner/image13.png', 926, 517,  align='center', caption='The online editor of Glitch') }}

El cuadro rojo de arriba indica el editor en línea donde escribirás HTML y CSS. El cuadro verde indica el botón que te llevará a la versión en vivo de la página que estas creando. El cuadro amarillo es el botón que te permite crear una copia de este proyecto y editarlo. El cuadro azul indica los archivos que tienes disponibles. En la carpeta “assets”, puedes encontar tus imágenes.

A lo largo de estos cursos, necesitarás varias imágenes para completar los ejercicios. Todas las imagenes que necesitas para completar estos cursos están contenidas en nuestros proyectos Glitch. Para ver las imágenes en tu proyecto, da clic en el listado de archivos del lado izquierdo del editor Glitch. Para obtener el enlace de cualquier imágen, selecciona la imagen de la lista de “assets” en el lado derecho. Haz clic en el boton “copy” junto a la URL en la ventana emergente que aparece. Podrás usar ese enlace donde sea que se necesite la imagen.

{{ image('/static/img/courses/beginner/image8.png', 843, 468,  align='center', caption='The assets view in Glitch') }}

{{ image('/static/img/courses/beginner/image12.png', 371, 354,  align='center', caption='The details pop-up (including URL) for an image in the assets collection') }}

En este curso, comenzaremos con una página HTML básica. Hemos creado un proyecto vació en Glitch que contiene unas cuantas imágenes, código de servidor que necesitarás mas tarde, y un archivo index.html con un título y una imágen sencilla.

Abre <a href="https://glitch.com/edit/#!/nosy-leech" target="_blank">este proyecto</a> para empezar. Da clic en el botón “Remix This” en la esquina superior derecha para crear un nuevo proyecto para que puedas editarlo. Puedes continuar usando este editor para este y los cursos futuros. En cada curso siguiente tendrás la oportunidad de iniciar con la versión de referencia a la solución.

No es necesario que uses Glitch para terminar estos entrenamientos. Sin embargo, parte del código requerido para terminar los ejercicios esta únicamente contenido en los ejemplos de Glitch. Si deseas usar otro editor, necesitarás usar los ejemplos de Glitch para encontar este código.

## Configurando el Validador AMP <a name="setting-up-the-amp-validator"></a>

Para detectar errores en nuestas páginas AMP, tenemos una herramienta valiosa en nuestras manos: el Validador AMP. Escribir páginas AMP válidas es la llave para ingresar a todos los beneficios que tiene el framework. El Validador AMP puede ser accesado de dos formas: via la extensión de Chrome, o agregando un parámetro a nuestra URL para que nuestra página AMP use el validador interno. Para los propósitos de este curso, te sugerimos usar la extensión de Chrome, ya que es más fácil de usar y accesar mientras construyes tu sitio.

- Para instalar la extensión de Chrome, visita el enlace [aqui](https://chrome.google.com/webstore/detail/amp-validator/nmoffdblmcmgeicmolmhobpoocbbmknc/related?hl=en).

- Para usar el Validador AMP interno, agrega `#development=1` al final de la dirección URL de tu página AMP, y abre la consola de desarrollo para ver los resultados. No es necesario agregar este parámetro si utilizas la extensión de Chrome.

## ¿Qué construiremos?

A lo largo de nuestros tres cursos, construirás un sitio web para Chico’s Cheese Bicycles Shop. Chico's ha desarrollado una bicicleta revolucionaria hecha completamente de queso. La demanda de sus nuevas bicicletas es muy alta, tanta que Chico's necesita levantar un sitio web tan rápido como sea posible. Cuando terminemos con estos tres cursos, el sitio de Chico's se verá como así:

{{ image('/static/img/courses/beginner/image14.png', 311, 550, align='center third', caption='How the site looks at the end of the Advanced Course') }}

Puedes dar clic en <a href="https://nice-consonant.glitch.me/" target="_blank">este enlace</a> para ver una vista previa en vivo. Mirar el todo el sitio. Tenemos vidios, un formulario de registro, una imagen de carrusel, y formas de compartir nuestro sitio en redes sociales. Abre el menu de navegación dando clic en el icono de las tres lineas (también llamado “hamburger menu icon”) en la esquina superior izquierda. Una vez que el menu se expande, da clic en el enlace “Our Products” para ir a la lista de productos. Intenta ordenar la lista de productos por precio y filtrando esta lista de productos por su categoría.

Elegimos el sitio de Chico's como nuestro modelo porque ofrece una colección de características que comunmente vemos en sitios web hoy en día. Fue creada por completo usando AMP. A lo largo de estas lecciones, podrás construir este sitio desde el inicio.

[/filter]
[filter level="advanced"]
## ¿Para quién es este curso?

Este curso esta diseñado para desarrolladores que buscan mejorar el rendimiento de los sitios web o simplemente entender AMP. En todos los tres cursos se asume que conoces HTML y CSS, y los cursos intermedios y avanzados se asume tener algo de experiencia con JavaScript.

## Sigue el Código con Glitch

Para completar el código de los ejemplos incluidos en estos cursos, podremos usar <a href="https://glitch.com/" target="_blank">Glitch</a>. Glitch es un editor de código en línea que te permite crear y visualizar sitios web sin la necesidad correr un servidor en tu computadora. En lugar de esto, tu servidor se encuentra dentro de Glitch.

El Editor de código Glitch luce así:

{{ image('/static/img/courses/beginner/image13.png', 926, 517,  align='center', caption='The online editor of Glitch') }}

El cuadro rojo de arriba indica el editor en línea donde escribirás HTML y CSS. El cuadro verde indica el botón que te llevará a la versión en vivo de la página que estas creando. El cuadro amarillo es el botón que te permite crear una copia de este proyecto y editarlo. El cuadro azul indica los archivos que tienes disponibles. En la carpeta “assets”, puedes encontar tus imágenes.

A lo largo de estos cursos, necesitarás varias imágenes para completar los ejercicios. Todas las imagenes que necesitas para completar estos cursos están contenidas en nuestros proyectos Glitch. Para ver las imágenes en tu proyecto, da clic en el listado de archivos del lado izquierdo del editor Glitch. Para obtener el enlace de cualquier imágen, selecciona la imagen de la lista de “assets” en el lado derecho. Haz clic en el boton “copy” junto a la URL en la ventana emergente que aparece. Podrás usar ese enlace donde sea que se necesite la imagen.

{{ image('/static/img/courses/beginner/image8.png', 1686, 936,  align='center', caption='The assets view in Glitch') }}

{{ image('/static/img/courses/beginner/image12.png', 1484, 1416,  align='center', caption='The details pop-up (including URL) for an image in the assets collection') }}

En este curso, comenzaremos con una página HTML básica. Hemos creado un proyecto vació en Glitch que contiene unas cuantas imágenes, código de servidor que necesitarás mas tarde, y un archivo `index.html` con un título y una imágen sencilla.

Abre <a href="https://glitch.com/edit/#!/nosy-leech" target="_blank">este proyecto</a> para empezar. Da clic en el botón “Remix This” en la esquina superior derecha para crear un nuevo proyecto para que puedas editarlo. Puedes continuar usando este editor para este y los cursos futuros. En cada curso siguiente tendrás la oportunidad de iniciar con la versión de referencia a la solución.

No es necesario que uses Glitch para terminar estos entrenamientos. Sin embargo, parte del código requerido para terminar los ejercicios esta únicamente contenido en los ejemplos de Glitch. Si deseas usar otro editor, necesitarás usar los ejemplos de Glitch para encontar este código.

## Configurando el Validador AMP <a name="setting-up-the-amp-validator"></a>

Para detectar errores en nuestas páginas AMP, tenemos una herramienta valiosa en nuestras manos: el Validador AMP. Escribir páginas AMP válidas es la llave para ingresar a todos los beneficios que tiene el framework. El Validador AMP puede ser accesado de muchas maneras. 

- Instalando la extensión de Chrome [aqui](https://chrome.google.com/webstore/detail/amp-validator/nmoffdblmcmgeicmolmhobpoocbbmknc/related?hl=en).

- Simplemente usa el Validador AMP interno. Agrega `#development=1` al final de la dirección URL de tu página AMP, y abre la consola de desarrollo en tu navegador.

## ¿Qué construiremos?

A lo largo de nuestros tres cursos, construirás un sitio web para Chico’s Cheese Bicycles Shop. Chico's ha desarrollado una bicicleta revolucionaria hecha completamente de queso. La demanda de sus nuevas bicicletas es muy alta, tanta que Chico's necesita levantar un sitio web tan rápido como sea posible. Cuando terminemos con estos tres cursos, el sitio de Chico's se verá como así:

{{ image('/static/img/courses/beginner/image14.png', 311, 550, align='center third', caption='How the site looks at the end of the Advanced Course') }}

Puedes dar clic en <a href="https://nice-consonant.glitch.me/" target="_blank">este enlace</a> para ver una vista previa en vivo. Selecciona “Our Products” para ir a la lista de productos. 

Elegimos el sitio de Chico's como nuestro modelo porque ofrece una colección de características que comunmente vemos en sitios web hoy en día. Fue creada por completo usando AMP. A lo largo de estas lecciones, podrás construir este sitio desde el inicio.
[/filter]
