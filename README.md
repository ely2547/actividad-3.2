# actividad-3.3

El código CSS contiene varios efectos visuales que se aplican a diferentes elementos de la página.

>Efecto de animación en el título principal de la página: La regla CSS para el selector "h1" aplica un estilo al título principal de la página. Además de establecer el color de texto y el fondo, se utiliza una animación llamada "moveAndChangeColor" para crear un efecto de cambio de color y movimiento. La animación se define utilizando la regla "@keyframes" y se aplica al título principal mediante las propiedades "animation-name", "animation-duration" y "animation-iteration-count".

>Sombra y borde en las recetas: La regla CSS para el selector ".receta" aplica un estilo a las recetas de la página. Se establece un margen, un borde y una sombra para crear un efecto visual de separación y profundidad en cada receta.
>Sombra y bordes redondeados en los títulos de las recetas: La regla CSS para el selector ".receta h2" aplica un estilo a los títulos de las recetas. Se establece un color de texto, un fondo, un relleno y bordes redondeados para resaltar los títulos de las recetas. Además, se agrega una sombra para crear un efecto de profundidad.
>Sombra en las imágenes de las recetas: La regla CSS para el selector ".receta img" aplica un estilo a las imágenes de las recetas. Se establece un ancho del 100%, una altura automática y una sombra para crear un efecto de sombreado en las imágenes.

>Efecto de escala de grises en las imágenes de las recetas: La regla CSS para el selector ".recetaimg" aplica un estilo a las imágenes de las recetas. Se establece un ancho del 100%, una altura automática y un filtro de escala de grises del 100%. Además, se agrega una transición para suavizar el cambio de escala de grises a color cuando se pasa el cursor sobre la imagen.

>Efecto de transición en las imágenes del carrusel: La regla CSS para el selector ".carousel-image" aplica un estilo a las imágenes del carrusel. Se establece una posición absoluta, una opacidad inicial de 0 y una transición de opacidad para crear un efecto de transición suave al cambiar las imágenes en el carrusel.

>Efecto de subrayado en los enlaces del menú: La regla CSS para el selector ".menu2 a:before" aplica un estilo a los enlaces del menú. Se agrega un subrayado animado utilizando la propiedad "before" y se establecen las propiedades de tamaño, posición y color para crear un efecto de subrayado al pasar el cursor sobre los enlaces.

El archivo index.html comienza con la etiqueta <!DOCTYPE html>, que define el tipo de documento como HTML5. Se utiliza la etiqueta <html> para indicar el inicio y el final del documento. Dentro de la etiqueta <html>, encontramos dos secciones principales: <head> y <body>.

Sección <head>:La sección <head> contiene información sobre el documento HTML, como el título de la página, enlaces a archivos CSS y metadatos. La sección <head> contiene las siguientes etiquetas:

<title>: Esta etiqueta define el título de la página que se muestra en la pestaña del navegador. 	 	
<meta charset="UTF-8">: Esta etiqueta especifica la codificación de caracteres utilizada en el documento. 	
<link rel="stylesheet" 	type="text/css" href="styles.css">: Esta etiqueta enlaza un archivo CSS externo llamado styles.css para aplicar estilos a la página. 	

Sección <body>: La sección <body> contiene el contenido visible de la página web. Aquí es donde se encuentran las etiquetas que definen la estructura y el contenido de la página. Esta sección contiene las siguientes etiquetas:

<header>: Esta etiqueta define el encabezado de la página, que generalmente contiene el logotipo y el título principal. 	 	
<nav>: Esta etiqueta define una sección de navegación que contiene enlaces a otras páginas o secciones del sitio web. 		
<main>: Esta etiqueta define el contenido principal de la página. 		
<section>: Esta etiqueta define una sección lógica o temática de la página. 	
<article>: Esta etiqueta define un artículo independiente dentro de una página. 	 	
<aside>: Esta etiqueta define un contenido relacionado pero independiente del contenido principal. 		
<footer>: Esta etiqueta define el pie de página.

Además de estas, también se utilizan etiquetas como <h1>, <h2>, <p>, <a>, <img>, <ul>, <li>, entre otras, para definir encabezados, párrafos, enlaces, imágenes, listas y más.

El script JavaScript incluido en index.html selecciona un conjunto de imágenes con la clase "carousel-image" y las muestra de forma cíclica cada 5 segundos. Esto se logra mediante la función showImage() y la función setInterval() que llama a showImage() cada 5000 milisegundos.
Por otro lado contiene un fragmento de código que incrusta un video de YouTube en la página web. El video se muestra en un contenedor con la clase "sticky-video".
