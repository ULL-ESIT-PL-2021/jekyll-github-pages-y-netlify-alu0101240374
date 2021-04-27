# Práctica: Jekyll

## Que son Jekyll y Liquid

Para esta práctica construiremos una página web personal usando jekyll, que es un generador de páginas estáticas. Para lo básico de jekyll se realizó el tutorial presente en la documentación oficial. El enlace es el siguiente: https://jekyllrb.com/docs/step-by-step/01-setup/  
El contenido de la página es bastante más avanzado que lo que se aborda en este tutorial pero sirve para un primer contacto con los conceptos más básicos.

## Características principales de la página

La página usa un directorio \_data para gestionar los enlaces de la sidebar de la izquierda de la página que sirve para navegar por el sitio web. La configuración del núcleo de la página se encuentra en \_config.yml, aquí indicamos por ejemplo el baseurl que usamos para cada despliegue, esto lo abordaremos mas adelante en el apartado de _baseurl y url_. También encontramos los defaults, que sirven para indicar el layout según el tipo, si post o collection por ejemplo. PAra los layouts se proporciona el directorio _layouts, que añade el layout de collections, aparte de los que vienen includos con el tema elegido. Procesamientos con Liquid se hacen varios, la mayoría se usan para iterar sobre elementos, como por ejemplo para los elementos de la sidebar. En el directorio _includes encontramos trozos de código que podemos reutilizar en cualquier layout. Por último, hacemos uso de las tags, para facilitar la organización de nuestro sitio web.

## Tema usado

Para la práctica se recomiendo usar Minimal Mistakes, pero para ñadir un toque de originalidad se ha usado Fresh, este es el estado original de la página si usamos este tema.

FOTO

Tras haber instalado la plantilla, se cambiaron elementos como las redes sociales de la sidebar, o se añadió el layout para las collections.

## Despliegue e Github Pages