# Mi proyecto

El ejercicio consiste en replicar una página web que nos viene dada desde Adalab para tener la oportunidad de practicar todo lo aprendido en el módulo 1 de maquetación.

A nivel de tecnologías, he trabajado con HTML, CSS, Flexbox, Media Queries, Github, Sass, Grid, etc. También he utilizado el Adalab Web Starter Kit como herramienta para organizar el ejercicio.

# Estructura

La web consta de una única página inicial que contiene varias secciones, por lo que se ha dividio el HTML en función de estas para darle mayor orden y legibilidad: 

- *Encabezado*: llamado "header.html", es la sección inicial que contiene el menú en forma de hamburguesa. Al hacer click sobre él, nos dirige a la web de adalab.es. Se mantiene fijo a medida que hacemos scroll en la página.

- *Sección 1 o Hero*: llamada "first.html", es la sección que contiene la foto principal y el título de la página. Al final encontramos una imagen en forma de flecha que, si la pulsamos, nos envía a la tercera sección de esta misma página.

- *Sección 2*: llamada "second.html", es la sección que contiene el lema de la página y un botón de "Comprar" que nos dirige, de nuevo, a la página web de adalab.es.

- *Sección 3*: llamada "third.html", es la sección que contiene el grueso de la información para el usuario. Al tener varias subsecciones dentro con una misma estructura, se ha creado un partial dentro llamado "info.html" para reutilizar su estructura y practicar la creación de partials en html. Por último, encontramos otro botón llamado "Empezar ahora" que nos dirige a la web de adalab.es.

- *Pie de página*: llamado "footer.html", es la sección final de la web. Consta de tres columnas, teniendo todas links a la web de Adalab salvo la de copyright.  

# Estilos

- Se ha seguido un diseño predeterminado desde la plataforma Zeplin.
- Se han creado variables tanto para los colores, como para los tipos y tamaños de fuentes.
- Se han aplicado los estilos al html mediante Sass, siguiendo la nomenclatura BEM y el sistema de anidación adecuado.
- En la sección 1, en la sección 3 y en la sección pie de página se ha aplicado Flexbox, mientras que en la sección 2 se ha aplicado Grid.
- Al poner el cursor del ratón sobre los links de la web, aparece un pequeño texto que nos indica que vamos a visitar la web de Adalab.

# Instalación y uso

# Estado del proyecto

# Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles.
