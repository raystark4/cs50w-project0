# Project 0

Web Programming with Python and JavaScript

Este Project 0 trata acerca del ajedrez, una pagina informativa sobre el origen, el creador de dicho juego, los mejores jugadores desde el inicio de su creacion y quienes se han marcado en la historia de este deporte, asi mismo los mejores jugadores en la actualidad, informacion relevante acerca de ellos, como su pais de origen, su puntuacion (ELO) entre otras cosas. También informacion basica para entender y asi comenzar a jugar, y los campeonatos mundiales que se ha venido dando a lo largo de la historia de este deporte.

La carpeta Project0 contiene dos carpetas, un index.html y un README.md:

"static" : carpeta "img": en ella se encuentran las carpetas que alojan a las imagenes y archivos multimedia qie he utilizado en todo el proyecto. Carpeta "css": en dicha carpeta estan los archivos SCSS de SASS, los cuales al compiarlos crea dos archivos uno con extension (.css.map) y el (.css) que reconoce html. He creado un archivo para cada archivo .html para llevar mas orden y control de mis estilos al momento de aplicarlos.

"templates" : Esta carpeta contiene los archivos (.html) que enseguida les explicare

Archivos .html:
index.html: este archivo muestra el inicio de mi pagina, con informacion relevante de cada tema que estoy abordando, es un pequeño vistazo de lo que contiene todo este project, los mejores jugadores, card de bootstrap que contiene informacion del origen, próximo campeonato mundial de ajedrez, info del campeon mundial vigente Magnus Carlsen, un carusel de los eventos mundiales, siendo estas las olimpiadas mundiales de ajedrez que se realizan en diferentes a paises del mundo.

historia.hmtl : este archivo se trata acerca de la historia del ajedrez, muestra una teoria de quien fue el creador de dicho juego, el origen que fue en la india y como ha venido evolucionando al pasar de los años, llegando a tener jugadores excepcionales, mostrando en una galeria de fotos estos de iconicos jugadores del pasado y tambien los actuales, en esta area si pasa el cursor encima de la foto muestra el nombre de la persona que se encuentra reflejada en la galeria.

jugadores.html : esta seccion esta dedidaca a mostrar informacion relevante de la mejor jugadora de ajedrez de nuestro pais, y los top en el ranking a nive mundial, siendo el primer lugar y campeon mundial Magnus Carsel, siguiendolo en el segundo puesto Fabiano Caruana, y otros grandes ajedrecistas como el japones Hikari Nakamura, se muestra una tabla del ranking por la FIDE, en dicha tabla utilice los componentes de bootstrap.

comojugar.html : en este archivo se muestra la informacion basica para entender el juego del ajedrez, por ejemplo, en que consiste este juego, sus caracteristicas, el nombre de cada pieza que esta en el tablero, los movimientos especificos de cada pieza, nombre de libros que pueden ayudar a entenderlo de una manera más rápida y fácil.

campeonatos.html : este archivo es la parte final de mi project0, lo hice utilizando componentes y herramientas de boostrap para practicar esta area, se muestra todos los eventos importantes que se ha realizado a nivel mundial, una descripcion de la organizacion que esta al mando de todos estos eventos (FEDE), los campeonatos y toreneos y tambien una tabla donde se muestran los datos de las olimpiadas que se han venido dando, desde la primera hasta la mas actual que se realizo en 2022.

Archivos .scss:
style.scss: este archivo contiene las propiedades css para darle estilos al index.html, tiene dos variables de sass las cuales tienen colores para titulos y parrafos, un identidicador universal (*), selectores de clase (.) y de Id (#), anidaciones, y una herencia, pseudoclase :nth-of-type y media Q para adaptar la pantalla a dispositivos mas pequeños.

jugadores.scss:
style.scss: este archivo contiene las propiedades css para darle estilos al jugadores.html, se encuentra una variable sass llamada $color-primeraLetra: que tambien contiene un color que se le aplica a la primera letra de un parrafo, anidamiento, selector de Id (#), media Q, para hacer responsive en pantallas de 320px, etc.

historia.sccs: este archivo contiene las propiedades css para darle estilos al historia.html, tengo 6 variables de sass, divididas en colores, y propiedades de padding, width, max-width, anidamientos, pseudoelemento ::after apliado al borde de un titulo, pseudoclase :hover para la galeria de fotos, y media Q para adaptar a pantallas mas pequeñas.

comojugar.scss: este archivo contiene las propiedades css para darle estilos al comojugar.html, hice una herencia llamada span, que es para un texto en especifico en la parte de los titulos en de los libros, una variable sass para el color de las listas y un selector de id (#).

campeonatos.scss: este archivo contiene las propiedades css para darle estilos al campeonatos.html, se encuentra una herencia llamada %paddinggeneral, que se le aplica a los textos e imagenes informativas, media Q para adaptar de mejor manera las imagenes a pantallas pequeñas y medianas.

Archivos .css y .css.map: Estos archivos son el resultado de las compilaciones de los archivos scss que estoy empleando como hojas de estilo en este project

Esto es mi project 0 - Raymond García