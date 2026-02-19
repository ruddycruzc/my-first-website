# Informe del proyecto: The Good Breakfast

## Resumen general
Pequeña página de práctica HTML/CSS con tres archivos principales: `index.html`, `style.css` y `README.md`. Objetivo: crear una estructura básica de web con navegación, título, imagen y pie de página.

## Archivos y descripción
- **[index.html](index.html)**: Estructura principal del sitio. Contiene un `<header>` con una lista de navegación (`<ul class="navegacion">`), un `<main>` con la sección `.titulo` (título, párrafo e imagen) y un `<footer>`.
- **[style.css](style.css)**: Estilos del proyecto. Define tipografía, fondo y estilos para `.navegacion` y `.titulo`.
- **[README.md](README.md)**: Enunciado del ejercicio y directrices, incluye instrucciones paso a paso para las iteraciones.

## Cambios realizados (por mí)
- Corregí el selector CSS para aplicar `list-style: none` y resetear `margin`/`padding` en la navegación; moví `list-style: none` a `.navegacion` y añadí `margin:0; padding:0;`.
- Eliminé una regla duplicada que añadía el separador `|` en dos sitios y dejé sólo:
  - `.navegacion li:not(:last-child) a::after { content: " | "; }`

## Problemas detectados y recomendaciones
- Imagen con atributo `src` mal formado en `index.html`:
  - Línea actual: `<img src="https://i.postimg.cc/htxcJGB6/ZKkCecn.jpg>" alt="Imagen de desayuno">`
  - Recomendación: quitar el carácter `>` dentro del `src` y asegurar que la etiqueta termine `>` correctamente, por ejemplo:
    - `<img src="https://i.postimg.cc/htxcJGB6/ZKkCecn.jpg" alt="Imagen de desayuno">`
- Accesibilidad / semántica:
  - Usar `<nav>` alrededor de la lista de navegación en lugar de solo `<header>` para mejorar semántica. Ejemplo:
    - `<nav><ul class="navegacion">...</ul></nav>`
- Diseño / estilo:
  - El `body` tiene `background-color: red;` (probablemente temporal). Revisar si ese color es intencional.
  - Si se quiere ocultar completamente los bullets en todas las listas por defecto, considerar añadir:
    - `ul { margin: 0; padding: 0; list-style: none; }`
- Separadores en navegación:
  - Ya está implementado el separador entre enlaces con `::after` en los `li` excepto el último. No usar otra regla `a::after` global para evitar duplicados.

## Pasos siguientes sugeridos
1. Corregir la etiqueta `<img>` en `index.html` (ver recomendación arriba).
2. Considerar envolver la navegación con `<nav>` y mejorar los textos de los enlaces a mayúsculas y/o traducir según idioma objetivo.
3. Revisar color de fondo y paleta para accesibilidad (contraste).
4. Validar la página con https://validator.w3.org/ y corregir errores que aparezcan.

---
Generado automáticamente: informe creado y guardado como `informe-proyecto.md`.
