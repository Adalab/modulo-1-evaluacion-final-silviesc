# Mi proyecto

El ejercicio consiste en replicar una página web que nos viene dada desde Adalab para practicar todo lo aprendido en el módulo 1 de maquetación.

A nivel de tecnologías, he trabajado con HTML, CSS, Flexbox, Media queries, Github, Sass, Grid, etc. También he utilizado el Adalab Web Starter Kit como herramienta para organizar el ejercicio.

# Estructura

La web consta de una única página inicial que contiene varias secciones, por lo que se ha dividio el html en función de estas para darle mayor orden y legibilidad: 

- __Encabezado__: llamado "header.html", es la sección inicial que contiene el menú en forma de hamburguesa. Al hacer click sobre él, nos dirige a la web de adalab.es. Se mantiene fijo a medida que hacemos scroll en la página.

- __Sección 1 o Hero__: llamada "first.html", es la sección que contiene la foto principal y el título de la página. Al final encontramos una imagen en forma de flecha hacia abajo que, si la pulsamos, aumenta ligeramente de tamaño y nos envía a la tercera sección de esta misma página.

- __Sección 2__: llamada "second.html", es la sección que contiene el lema de la página. Contiene un botón de "Comprar" sobre el que, al pasar el ratón por encima, aumenta también de tamaño y cambia sus colores. Este botón nos dirige de nuevo a la web de adalab.es.

- __Sección 3__: llamada "third.html", es la sección que contiene el grueso de la información para el usuario. Al tener varias secciones internas con la misma estructura, se ha creado un partial llamado "info.html" para reutilizar su estructura y practicar la creación de partials en html. Al final encontramos otro botón llamado "Empezar ahora" que tiene las mismas características de navegación y estilo que el botón "Comprar" (salvo por los colores, que están a la inversa).

- __Pie de página__: llamado "footer.html", es la sección final de la web. Consta de tres columnas con varios items dentro de cada una, teniendo todos ellos links a la web de Adalab salvo los de la columna copyright. En este caso, contamos en la parte superior de la sección con otra imagen en forma de flecha hacia arriba que, si pulsamos, nos dirige de nuevo al inicio de la propia página. Asimismo, al pasar el ratón por toda esta sección, se agranda ligeramente para hacer más legible su lectura y mejorar la experiencia de usuario.

# Estilos

- Se ha seguido el diseño predeterminado desde la plataforma Zeplin.
- Se han creado variables tanto para los colores, como para los tipos y los tamaños de fuentes.
- Se han aplicado los estilos al html mediante Sass, siguiendo la nomenclatura BEM y el sistema de anidación adecuado.
- En la sección 1, en la sección 3 y en la sección pie de página se ha aplicado Flexbox, mientras que en la sección 2 se ha aplicado Grid.
- Se han aplicado las media queries necesarias para hacer un diseño responsive que la web se ajuste a la ventana o dispositivo de cada usuario.
- Se han tenido en cuenta temas de accesibilidad a la hora de crear la web, empleando buenas prácticas para ello como el uso de textos alternativos para las imágenes, la utilización de etiquetas semánticas para el html, la inclusión de mensajes antes de hacer click en los links externos, etc.

# Puesta en marcha 

- Para visualizar la web, basta con hacer click en el enlace de Github Pages que se encuentra en la parte superior derecha de la pantalla, en el apartado de “About”. 

- En caso de querer visualizarlo en local, los pasos a seguir son los siguientes:

    1. Instalación de Visual Studio Code.
    2. Clonar el repositorio en la terminal de VS Code con el siguiente comando: “ git clone https://github.com/Adalab modulo-1-evaluacion-final-silviesc.git“.
    3. Descargar todo el proyecto mediante el comando “git pull”.
    4. Realizar el comando “npm install” para instalar los node modules necesarios para la ejecución del proyecto.
    5. Introducir en la terminal el comando “npm run dev” para que sea mostrado por el navegador.

- La web es compatible con los navegadores Mozilla, Chrome y Safari. 

# Estado del proyecto

El proyecto quedará finalizado y entregado para su corrección el jueves 14 de diciembre de 2023. Quedaré pendiente de feedback y, en caso de hacer alguna modificación posterior, será desde la rama "dev". 

# Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles.
