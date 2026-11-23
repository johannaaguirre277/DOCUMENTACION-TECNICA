# Página de Documentación Técnica — CSS Responsivo

Proyecto práctico de diseño web responsivo basado en las historias de usuario de **freeCodeCamp**, enfocado en estructura semántica HTML5, unidades relativas, *media queries* y diseño adaptable entre escritorio y dispositivos móviles.

## Estructura del proyecto

- `index.html`: Contiene la estructura principal con `<nav id="navbar">`, `<main id="main-doc">`, las cinco secciones `.main-section`, encabezados, bloques `<p>`, ejemplos `<code>`, listas `<ul>`/`<li>` y el enlace a la hoja de estilos externa `styles.css`.
- `styles.css`: Define la barra lateral fija a la izquierda en pantallas de escritorio (`position: fixed`), la tipografía y espaciado del contenido principal, y una *media query* (`@media (max-width: 800px)`) para adaptar la navegación en pantallas pequeñas.

## Características implementadas

- Navegación fija lateral en escritorio y apilada en pantallas estrechas.
- Enlaces internos (`.nav-link`) sincronizados con los encabezados y los `id` de cada sección (`#Introduccion_al_Diseno_Responsivo`, `#Unidades_Relativas`, `#Media_Queries`, `#Imagenes_Flexibles` y `#Enfoque_Mobile_First`).
- Cumplimiento de los requisitos mínimos de etiquetas `<p>`, `<code>` y `<li>` dentro de `.main-section`.
- Enlace externo a `styles.css` desde el `<head>`.

## Uso local

Abre `index.html` directamente en tu navegador o sirve la carpeta del proyecto con un servidor local para revisar el diseño y ejecutar las pruebas correspondientes.