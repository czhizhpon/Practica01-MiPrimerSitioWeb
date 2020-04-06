# Practica01-MiPrimerSitioWeb
Creación de mi primer sitio web HTML
1.	Desarrollo de las páginas web.

Tema: El tema central es la divulgación de información sobre videojuegos, hardware, software y todo lo que conlleva, para lo cuál se creó 9 archivos HTML, con las siguientes etiquetas:

Para esta práctica se usó una estructura básica, siendo index.html el punto referencia para las demás. La etiqueta “<head>” tiene la misma funcionalidad para el resto de las páginas, donde se declaró el conjunto de caracteres “utf-8”, y las keywords correspondientes a la subtemática de cada archivo. 

Para esta práctica se usó como estándar la siguiente estructura, que contiene el inicio de <body>, donde la etiqueta <header> hace referencia al encabezado del sitio, que incluye el logo y un menú de navegación con la etiqueta <nav>, que cuenta con los apartados: inicio, juegos, novedades, hardware, descubre, eventos, gameplays, soundtrack y sobre nosotros. 

Cabe recalcar que cada archivo HTML de la práctica cuenta con este encabezado, para efectos de estética del sitio. Sin embargo, se incluirá capturas de las etiquetas <head> y <body> para efectos de documentación. 
 
La etiqueta <footer> también se usó como un estándar para todos los archivos HTML, donde se escribe al autor, el email con la etiqueta <a>, y un “href=mailto”, para que el usuario puede enviar un correo con un click, con la misma intención se usó “href=tel”, con el número de teléfono del autor, y la leyenda Todos los derechos reservados con su símbolo, para lo cual se usó “&copy;”.

1.	index.html: 
Este archivo HTML tiene la función de dar la bienvenida a los usuarios de la página, presentando las novedades del sitio, normalmente una noticia que esté publicada en el apartado de Novedades. 

•	Se usó la etiqueta <h1> para escribir la temática principal del sitio, por ejemplo, en index.html da la bienvenida. 

•	Se usó la etiqueta <section> para abrir el tema de Descubre, que hace referencia a noticias y novedades que el sitio quiera mostrar.

•	Se usó la etiqueta <article> para presentar la noticia o novedad que el sitio quiera mostrar. El cual contiene la etiqueta <a> para que el usuario pueda dar click en Novedades, y puede abrir el apartado de Novedades del sitio. Cuenta con un pequeño párrafo con la etiqueta <p>, se optar por no usar más de un párrafo, ya que el resto lo puede ver en el apartado que le corresponda. 

•	También contiene un <iframe>, dentro de un <blockquote>, ya que es un recurso de otro sitio, y para dar un pequeño énfasis al video, esta etiqueta es omitida en el siguiente <article>, y en véz de ello se usó una imagen. Donde el usuario puede hacer click, ya que la imagen posee una etiqueta <a>, que le llevará al sitio en cuestión.

•	En este caso, se usó <aside> fuera de <article>, ya que no corresponde al tema que se estaba hablado, ya que habla de unos rumores no confirmados de otra fuente, donde el usuario puede dar click al dominio del sitio donde fue tomado, porque cuenta con un <a> con atributo “target=”_blank”” que abrirá el enlace en otra página en blanco para que no se cierre el sitio.
  
  
2.	events.html: 
Este archivo presenta los eventos sobre videojuegos que estén ocurriendo en la actualidad.

•	Se usó <h1> para mostrar “Eventos” y hacer referencia de lo que trata el apartado. Se usó un <section> junto a <h2> para describir de lo que trata esta sección, en este caso E-Sport. Para este sitio se usó un estándar, por lo que cada articulo que se escriba en él, debe contar con:
o	Una etiqueta <article>, seguido de <h3> con el título del artículo.
o	Un apartado multimedia, una foto o video que hable sobre el tema.
•	También se usó <ul>, junto a <li>, para describir una lista desordenada de las actividades que se llevarán a cabo.

•	El sitio tiene otro artículo, con la misma estructura de la anterior, que da como finalizado a la página web.
 
3.	gameplays.html
Este sitio se encarga de presentar playlists de juegos modo historia y modalidad online.
 
Se usó <h1> para presentar la temática, “Gameplays”, donde tiene dos secciones <section>, Playlist, donde contiene playlist de franquicias de videojuegos, como Star Wars Jedi. 

Para exponer los videos se usó <iframe>, con los atributos, “width=850”, “height=500”, src con la dirección embed de la lista, para la cual, hay que incluir después de /embed/, “playlist?list=id”, donde id, es el identificador de la lista en cuestión. También se permitió: accelerometer, autoplay, encrypted-media, gyroscope, picture-in-picture. También se permitió entrar en la modalidad pantalla completa con “allowfullscreen”. Todo esto dentro de un <blockquote> con la intención de hacer un énfasis y porque es un recurso de otro sitio web. Además de incluir un párrafo con la descripción del video en cuestión.

La siguiente sección trata de Multijugador, donde se usó la misma estructura para los <article> del anterior <section>.

Finalmente, el pie de página de este archivo.

4.	soundtrack.html
En este sitio se hace una recopilación de los mejores soundtracks sobre videojuegos.

Se usó <h1> para especificar la temática del sitio, Soundtrack. Se planteó usar dos <section>, videojuegos y trailers, para diferenciar a los tipos de videojuegos, se usó <article>, <h3> se usó para el título de cada <article>, con un párrafo <p> que describe los soundtranks de los videojuegos. 

También se incluye una imagen con <img>, en este caso, con la imagen del álbum.
Para los audios se usó <audio>, dentro de una lista organizada <ol> y <li> para cada canción del álbum. 

Se usó un <aside> dentro del <article>, porque es un dato relacionado al tema principal.

El siguiente apartado, Trailers, se siguió la misma lógica del anterior. Con la diferencia de que este <aside>, está fuera del <article>, ya que no es un tema tan relacionado.
 
Finalmente, termina el archivo con el pie de página.

5.	hardware.html
En este apartado, se describen los componentes utilizados en computadoras o consoladas destinadas a los videojuegos.

El archivo de estructura con <h1> que describe la temática del sitio, “Hardware”. En este caso se usó dos <section>, uno para hardware centrado en PC/Laptops, y otro destinado para consolas. Cada sección posee <article>, donde se concentra la información del dispositivo en cuestión, cada <article> usa un <h3> para los títulos, cada articulo tiene una o varias imágenes con <img>, con los atributos, “width=500” y un “height=400”.
 
También se usó un <aside>, con una información que no se relaciona con el artículo, por lo que está fuera de él.
 
Para la estructura de la sección de consolas, se usó la misma estructura de la anterior.

También se usó un video con la etiqueta <video>, para la cual, se incluyeron los atributos, “width=854” para definir el ancho, “height=480” para definir la altura, y habilitamos los controles con “controls”. En src se puso un ruta relativa ../../videos para acceder a la carpeta donde están almacenados los videos, y se especifico que el formato del archivo es .mp4 con “type=”video/mp4””.
 
Finalmente se termina el archivo con el pie de página estándar para todos los archivos.
 
6.	news.html
En este apartado muestran las noticias relacionados al tema de videojuegos, hardware o software.

Se usó  <h1> para presentar el tema de lo que trata este sitio. Para este sitio se usó dos <section>, uno de ellos trata de videos y otro post, que trata de noticias presentadas en <article> escritos, con diferentes temas, ejemplo, realidad virtual. Para los títulos se usó <h3>, seguido de <blockquote>, que agrupa los diferentes videos, con <h4> para los títulos de cada video y una descripción en un párrafo <p>. Para los videos se usó <iframe> con videos enlazados de YouTube.
 
En la siguiente sección “Posts” con <h2>, describe noticias en escrito, donde cada <article> diferencia a los posts. Para los títulos se usó <h3>, seguido de los párrafos correspondiente, y una o varias imágenes con la etiqueta <img>.  

También se utilizó un <ul> lista no organizada, con su <li> para cada ítem.
  
Finalmente se termina con el pie de página estándar para todos los archivos HTML.

7.	about.html
En esta página se describe sobre qué trata la página web.

Se usó un <article>, con un <h1> para el título “Sobre Nosotros”, y un <img> con imagen centrada en el ambiente del sitio.
8.	find.html
En este sitio, se describen recomendaciones que el sitio proporciona a los usuarios.

Para el título se usó <h1>, en este sitio se usó dos <section> uno para Juegos y hardware recomendados. Para cada sección se usó <h2> para los títulos, cada juego se diferencia con <article> con títulos en <h3>. Para imágenes <img>, cada juego tiene un trailer con <frame>. 
  
•	Para describir los requerimientos se utilizaron tablas <tables>, con border = 2, como se pidió en la práctica, a pesar de ser un atributo que ya no está soportado en HTML 5. 

•	Para la tabla se usó, <th> para las celdas cabeceras, <td> para las celdas, las dos cuentas con los atributos “rowspan=2” que es para extender dos celdas de las filas, y “colspan=2” para extender las columnas, “scope” se usó para definir si es una celda cabecera de filas “row”, columnas “col”.
  
Para la siguiente sección se utilizó una estructura antes explicada, <h2> títulos, <article> para diferentes post relacionados al hardware, <img> para las imágenes, <iframe> para videos de YouTube.
 
También se usó un <aside> dentro del <article>, ya que es algo relacionado con el tema, pero no relevante para el mismo. Y finalmente termina con el pie de página estándar para todos los archivos HTML.

9.	games.html
En este apartado, describe datos informativos referente a sagas de videojuegos, con historia, requerimientos y videos relacionados.

En este caso se optó por utilizar un <nav> para navegar por las secciones de la página, con una lista ordenada <ol>, para lo cual, la etiqueta <a>, y los atributos, href para el enlace a las secciones, con lo cual, se debe incluir el archivo, numeral y el id, explicado en el siguiente apartado.
 
Se usó <h1> para el título sobre el videojuego que se va a hablar, la página tiene 4 <section> que son: historia, características, requerimientos y videos. Donde tiene 3 <article>, que son algo nuevo, que describe las novedades, legado y críticas.
  
También se usaron tablas para describir los requerimientos, donde ya se explicó anteriormente. Solo una tabla incluye el “border=2” como se indica en la práctica.
Algo diferente, es que se usó <iframe> para clips de twitch. Que tiene la misma estructura, utilizada anteriormente, pero con src diferente.
Finalmente, después de todas las secciones, termina el archivo con el pie de página estándar para todos los archivos HTML.
