# KID'S SHOP

Este proyecto consiste en el desarrollo de una página web responsive de ropa para niños partiendo de un diseño compartido en Zeplin.

Las técnologías y lenguajes usados para la realización de este proyecto han sido:

- **Starter Kit de Adalab**. Creado con **node y vite**. Para crear una plantilla del proyecto HTML.
- **Repositorio git y GitHub**. Para el control de versiones.
- **Lenguajes HTML y CSS**. HTML para la estructura del proyecto y CSS para la hoja de estilos.
- **Prepocesador SASS**. Para la creación de código CSS estándar.
- **Marco de trabajo BEM**. Para una mayor legibilidad y mantenimiento del código CSS.

## REQUISITOS

### Diseño
Para la ejecución del diseño se ha usado:
- Sass.
- Flexbox y CSS Grid.
- Media queries: mobil(320px), tablet(768px) y desktop (1280px).
- Interacciones mediante transiciones (E).

### Maquetación
La maquetación cumple los siguientes requisitos:
- Bóton de hamburguesa: posicionamiento fijo en la esquina superior izquierda para no desaparecer al hacer scroll.
- Módulo 1 (hero-Comienzos compartidos): maquetación con Flexbox, altura del alto de la ventana del navegador e imagen como fondo de la sección (background-image).
- Módulo 2 (Tu tienda de deporte): maquetación con Flexbox.
- Módulo 3 (Vuelta al cole): maquetación con GRID adaptada a cada tamaño media querie.
- Módulo 4 (footer): maquetación con Flexbox y enlaces en los textos de las columnas "Zapatillas" y "Twitter" (E). 

**NOTA:** En el módulo 3, cada "card" (imagen y texto) creada para esa sección está maquetada con Flexbox.

### Interacción
El proyecto cumple con las siguientes interacciones:
- Enlace entre el botón de flecha del Módulo 1 (hero) que lleva al Módulo 3 (Vuelta al cole).
- Enlace entre el botón de flecha sobre el Módulo 4 (footer) que lleva al Módulo 1 (hero).
- Todos los enlaces del Módulo 4 (footer) llevan a la web de Adalab.
- :hover en los botones "Comprar" y "Vuelta al cole". Ambos dos cambian su tamaño durante un tiempo determinado con las propiedades transform y transition. El botón "Comprar" cambia de color (B).
- Animación en el bóton de flecha del Módulo 4 (footer), al pasar el ratón sobre él se desplaza hacia arriba un par de veces como en un salto (B). 

> **NOTA:** Todo estos puntos eran requisitos del proyecto. Aquellos marcados con una (E) eran Extras y con (B) eran un Bonus.

## INSTALACIÓN
Dentro de nuestro archivo de trabajo abrir una terminal BASH y clonar el repositorio de github.
Comprobar que estamos en la ruta del directorio adecuada. Posteriormente instalar las dependencias "node_modules" para la ejecución del framework Vite, e iniciar el proyecto. 

Clonar repositorio:

$ git clone https://example.com

Ruta directorio:

$ cd ../path/to/the/file

Instalación dependencias:

$ npm install

Iniciar proyecto:

$ npm start

## PUBLICACIÓN 
Primero generamos la página para producción. En la terminal BASH introducimos el comandos:
$ npm run push-docs

A continuación subimos el repositorio a la carpeta `docs/` que se acaba de generar. En la pestaña `settings` del repositorio ir al apartado de GitHub Pages y activar la opción **master branch /docs folder** 