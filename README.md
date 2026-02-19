# HTML Breakfast
Ejercicio para practicar etiquetas HTML:

## Objetivo
Estructurar el contenido de una página web mediante etiquetas HTML.

## Instrucciones

- Utiliza la lista de etiquetas que se adjunta para crear algo similar al siguiente diseño:

![Urban Toast](https://imgur.com/DhgcTot.png)

### Iteración 1+

- Haz un "fork" de este proyecto y clona el contenido desde tu repositorio.

### Iteración 2: Etiquetas de `<head>`
- Utiliza las etiquetas correctas para introducir en el fichero `index.html`, el siguiente contenido:
   - Idioma de la página: inglés
   - Caracteres utf-8 (Busca cual es el significado de estas siglas)
   - Título de la página que aparece en la pestaña del navegador: Urban Toast
### Iteración 3: Etiquetas de `<body>`
- Crea una barra de navegación con los siguientes enlaces: HOME, ABOUT US, DAILY OFFER, CONTACT US
- Título principal: The good breakfast
- Párrafo 1: Here you will find all sorts of delicious treats
- Imagen: https://i.postimg.cc/htxcJGB6/ZKkCecn.jpg
- Pie de foto: powered by biscuit.
- Párrafo de pie de página: From the oven with love

### Iteración 4: Párrafos
- Inserta el siguiente texto que explica algo sobre el restaurante:
"Our commitment is to use impeccable sourcing and quality ingredients to help 
  you code.An ongoing collaboration between the classroom staff and the development
   team allow us to iterate our content and give our students the coding 'fruits and
    vegetables' -mainly made of JavaScript- that they need to grow as a healthy 
    developer."
- Resalta las palabras "quality ingredients" con la etiqueta de texto importante

### Iteración 5: Citas
- Utiliza la etiqueta de cita en bloque para destacar la siguiente frase:  "Good code & good coffee, everyday"

### Iteración 6: Listas
- Crea un menú para indicar el café que servimos.
- Introduce una cabecera que indique el menú.
- Una lista de Cafés: Café latte, American, Machiatto, Capuccino
- Una lista de tés: Earl Grey, Green Tea, Rooibos

### Iteración 6: Bonus
- Transforma la lista anterior en una tabla.

### Iteración 7: Formulario de Reservas
- Crea un formulario de reservas, con el título "Reservas Aquí", para recoger la información de una reserva:
  - Una caja con etiqueta para recoger el nombre del cliente.
  - Una selección de opciones para elegir entre Snack or Breakfast
  - Una selección de opciones para elegir cuántas personas serán (de 1 a 4).
  - Un botón para enviar la información

### Iteración 8: Elementos del pie de página
- Añade un link ‘Contact Us’ en la sección del pie de página. Debería abrir la aplicación de correo del usuario para poder enviar un mail al equipo.
- Muestra el horario de apertura del restaurante

### Bonus track: Vídeo
- Cambia la imagen de la página por un vídeo.

### Bonus Bonus: Te atreves a darle estilo ??
- Aplica CSS para tener una página perfecta,

### Validaciones:

- Comprueba que tu página está correctamente estructurada con la herramienta: https://validator.w3.org/

### Entrega:
- Sube el ejercicio a tu repositorio de Github y adjunta la url del repositorio.

Aquí tienes una lista extensa y categorizada de las etiquetas HTML5 actuales, siguiendo el formato solicitado. He incluido tanto las etiquetas estructurales comunes como aquellas más específicas para semántica, multimedia y aplicaciones web.

## Lista de Etiquetas

**Estructura Básica y Metadatos**

* **`<!DOCTYPE html>`**: Define el tipo de documento y la versión de HTML (HTML5).
* **`<html>`**: Elemento raíz que encierra todo el contenido de la página.
* **`<head>`**: Contenedor de metadatos (información no visible) como título, scripts y enlaces a estilos.
* **`<body>`**: Contiene todo el contenido visible del documento (texto, imágenes, enlaces).
* **`<meta>`**: Define metadatos como la codificación de caracteres, autor, descripción y configuración del viewport.
* **`<title>`**: Establece el título de la página que aparece en la pestaña del navegador y en los resultados de búsqueda.
* **`<link>`**: Enlaza recursos externos, comúnmente usado para hojas de estilo CSS o iconos (favicons).
* **`<style>`**: Permite escribir código CSS directamente dentro del documento HTML.
* **`<base>`**: Especifica la URL base para todas las URLs relativas en un documento.

**Seccionamiento de Contenido (Semántica)**

* **`<header>`**: Define la cabecera de una página o sección (suele contener logos o navegación).
* **`<nav>`**: Define un bloque de enlaces de navegación principales.
* **`<main>`**: Especifica el contenido principal y único del documento (solo debe haber uno por página).
* **`<section>`**: Define una sección temática genérica dentro del documento.
* **`<article>`**: Representa contenido independiente y autónomo (artículo de blog, noticia, comentario).
* **`<aside>`**: Contenido relacionado indirectamente con el contenido principal (barras laterales, publicidad).
* **`<footer>`**: Define el pie de página de un documento o sección (copyright, enlaces legales).
* **`<address>`**: Proporciona información de contacto para el autor o propietario del documento.
* **`<h1>` a `<h6>**`: Encabezados de sección, donde `<h1>` es el más importante y `<h6>` el menos.

**Contenido de Texto**

* **`<p>`**: Define un párrafo de texto.
* **`<hr>`**: Representa un cambio temático entre párrafos (visualizado generalmente como una línea horizontal).
* **`<pre>`**: Define texto preformateado; preserva espacios y saltos de línea (ideal para código).
* **`<blockquote>`**: Indica que el texto encerrado es una cita larga de otra fuente.
* **`<ol>`**: Define una lista ordenada (numérica o alfabética).
* **`<ul>`**: Define una lista desordenada (con viñetas).
* **`<li>`**: Define un ítem dentro de una lista (`<ol>` o `<ul>`).
* **`<dl>`**: Define una lista de descripciones (diccionario o glosario).
* **`<dt>`**: Define el término en una lista de descripción.
* **`<dd>`**: Define la descripción o definición del término anterior.
* **`<figure>`**: Contenido autónomo, como ilustraciones, diagramas o fotos.
* **`<figcaption>`**: Define un título o leyenda para un elemento `<figure>`.
* **`<div>`**: Contenedor genérico de bloque para agrupar elementos y aplicar estilos (sin valor semántico).

**Semántica en Línea (Texto Inline)**

* **`<a>`**: Crea un hiperenlace a otras páginas, archivos o anclas.
* **`<span>`**: Contenedor genérico en línea para aplicar estilos o scripts a partes de texto.
* **`<br>`**: Inserta un salto de línea simple.
* **`<strong>`**: Define texto con gran importancia (generalmente se muestra en negrita).
* **`<em>`**: Define texto con énfasis (generalmente se muestra en cursiva).
* **`<small>`**: Representa comentarios secundarios o letra pequeña (como derechos de autor).
* **`<mark>`**: Representa texto resaltado o marcado por referencia (como un subrayador).
* **`<del>`**: Texto que ha sido eliminado del documento (tachado).
* **`<ins>`**: Texto que ha sido insertado en el documento (generalmente subrayado).
* **`<sub>`**: Texto subíndice (más bajo y pequeño).
* **`<sup>`**: Texto superíndice (más alto y pequeño).
* **`<code>`**: Define un fragmento de código de computadora.
* **`<kbd>`**: Representa una entrada del usuario (teclado).
* **`<abbr>`**: Define una abreviatura o acrónimo.
* **`<cite>`**: Define el título de una obra creativa (libro, película).
* **`<q>`**: Define una cita corta en línea.
* **`<time>`**: Representa una fecha u hora específica (útil para máquinas/buscadores).

**Imágenes y Multimedia**

* **`<img>`**: Inserta una imagen. Requiere `src` (fuente) y `alt` (texto alternativo).
* **`<audio>`**: Inserta contenido de sonido.
* **`<video>`**: Inserta contenido de video.
* **`<source>`**: Especifica múltiples recursos multimedia para `<video>`, `<audio>` o `<picture>`.
* **`<track>`**: Define pistas de texto (subtítulos) para `<audio>` o `<video>`.
* **`<picture>`**: Permite especificar múltiples fuentes de imagen para diferentes dispositivos/tamaños.
* **`<iframe>`**: Inserta un marco en línea que contiene otra página web o recurso externo.
* **`<embed>`**: Contenedor para una aplicación externa o contenido interactivo (plugins).
* **`<object>`**: Define un objeto incrustado (imágenes, PDFs, Flash, etc.).
* **`<canvas>`**: Se usa para dibujar gráficos vía scripting (generalmente JavaScript).
* **`<svg>`**: Define gráficos vectoriales escalables directamente en el código.

**Tablas**

* **`<table>`**: Define una tabla de datos.
* **`<caption>`**: Define el título de la tabla.
* **`<thead>`**: Agrupa el contenido de la cabecera de una tabla.
* **`<tbody>`**: Agrupa el contenido del cuerpo de una tabla.
* **`<tfoot>`**: Agrupa el contenido del pie de una tabla.
* **`<tr>`**: Define una fila en una tabla.
* **`<th>`**: Define una celda de encabezado (negrita y centrada por defecto).
* **`<td>`**: Define una celda de datos estándar.
* **`<col>`**: Especifica propiedades de columna para cada columna dentro de un elemento `<colgroup>`.
* **`<colgroup>`**: Especifica un grupo de una o más columnas para formato.

**Formularios**

* **`<form>`**: Define un formulario HTML para la entrada del usuario.
* **`<input>`**: Campo de entrada versátil. El atributo `type` define su comportamiento (text, password, checkbox, radio, submit, file, date, etc.).
* **`<label>`**: Define una etiqueta descriptiva para un elemento `<input>`.
* **`<textarea>`**: Define un control de entrada de texto multilínea.
* **`<button>`**: Botón clicable (puede enviar formularios o ser un botón genérico).
* **`<select>`**: Crea una lista desplegable.
* **`<option>`**: Define las opciones dentro de un `<select>` o `<datalist>`.
* **`<optgroup>`**: Agrupa opciones relacionadas dentro de un `<select>`.
* **`<fieldset>`**: Agrupa elementos relacionados dentro de un formulario (con un borde visual).
* **`<legend>`**: Define un título para el elemento `<fieldset>`.
* **`<datalist>`**: Especifica una lista de opciones predefinidas para controles `<input>`.
* **`<output>`**: Representa el resultado de un cálculo.
* **`<progress>`**: Representa el progreso de una tarea.
* **`<meter>`**: Representa una medida escalar dentro de un rango conocido (como uso de disco).

**Elementos Interactivos y Scripting**

* **`<details>`**: Crea un widget de divulgación que el usuario puede abrir y cerrar.
* **`<summary>`**: Define el encabezado visible para el elemento `<details>`.
* **`<dialog>`**: Define un cuadro de diálogo o ventana modal.
* **`<script>`**: Se usa para incrustar o referenciar un script ejecutable (JavaScript).
* **`<noscript>`**: Define contenido alternativo para usuarios que tienen scripts deshabilitados.
* **`<template>`**: Contenedor de HTML que no se renderiza al cargar, pero puede instanciarse luego mediante JavaScript.
* **`<slot>`**: Marcador de posición dentro de un componente web (`<template>`) que puede rellenarse con su propio marcado.
