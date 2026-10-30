# Aprendizajes, dificultades e interacción con la IA

## Contexto del proyecto

Este proyecto consiste en una página web educativa inspirada en el sitio de Disney. Está construida con HTML y CSS, sin JavaScript, y reúne distintas secciones: una barra de navegación, un banner principal, tarjetas de contenido, películas, parques, una oferta y un pie de página.

## Aprendizajes

- **Organización con HTML semántico:** etiquetas como `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>` ayudan a separar el contenido por propósito y hacen que la estructura sea más fácil de entender.
- **Diseño de componentes con CSS:** las tarjetas comparten clases y estilos, mientras que modificadores como `card--shop` y `card--park` permiten adaptar su presentación.
- **Uso de Flexbox y CSS Grid:** Flexbox organiza elementos en una dirección, como los elementos de la navegación, y Grid distribuye las tarjetas en filas y columnas.
- **Diseño adaptable:** las media queries reorganizan las cuadrículas según el ancho de pantalla. Por ejemplo, las tarjetas de tienda pasan de cuatro columnas a dos y después a una.
- **Consistencia en los estilos:** las propiedades personalizadas declaradas en `:root` permiten reutilizar colores, espacios y otros valores.
- **Imágenes y proporciones:** `object-fit: cover` y `aspect-ratio` ayudan a mantener una presentación uniforme en las imágenes de las tarjetas. `loading="lazy"` se utiliza para diferir la carga de imágenes que no aparecen al inicio.
- **Accesibilidad básica:** los textos alternativos de las imágenes y los estilos `:focus-visible` son importantes para describir el contenido y facilitar la navegación con teclado.

## Dificultades e inconvenientes identificados

1. **Mantener una composición ordenada con muchas secciones.** Cada sección tiene contenido y colores propios. Usar contenedores, clases específicas y una escala común de espaciado ayuda a conservar la coherencia visual.
2. **Adaptar las cuadrículas a distintos tamaños.** Una cantidad de columnas adecuada para escritorio puede resultar estrecha en un teléfono. Las media queries permiten cambiar la distribución, pero conviene revisar la página en varios anchos para detectar desbordamientos.
3. **Ajustar las imágenes de fondo.** Con `background-size: cover`, el fondo llena el espacio disponible, pero puede recortar partes de la imagen. La posición del fondo debe revisarse en pantallas grandes y pequeñas.
4. **Diferenciar una maqueta visual de una página funcional.** Varios enlaces usan `href="#"` y el formulario de búsqueda no tiene una función implementada. Por eso, los botones y enlaces son principalmente demostrativos y no deben confundirse con funcionalidades terminadas.
5. **Revisar el contenido para la audiencia.** La página combina textos en inglés y español. Si el sitio se publica para una audiencia concreta, sería conveniente unificar el idioma y comprobar que las etiquetas de accesibilidad describan el contenido con claridad.

## Interacción con la inteligencia artificial

El siguiente registro resume la interacción utilizada para preparar esta documentación:

> **Estudiante:** «Ayúdame a crear un documento Markdown con aprendizajes, inconvenientes o dificultades, e incluye la conversación o interacción con la inteligencia artificial que se utilizó como apoyo».
>
> **IA:** «Revisaré la estructura y los estilos del proyecto para redactar una reflexión relacionada con la página real. También incluiré un resumen de esta asistencia, sin presentar como hechos conversaciones anteriores que no aparecen en el registro».

### ¿Cómo fue útil el apoyo de la IA?

La IA ayudó a revisar la organización del HTML y los estilos CSS, identificar aprendizajes y aspectos que todavía podrían mejorarse, y ordenar esos puntos en un documento Markdown. La revisión del proyecto permite que el contenido se refiera a elementos concretos, como las cuadrículas, las media queries, las imágenes y los enlaces de ejemplo.

La IA funciona como apoyo para analizar y redactar; es importante que el estudiante lea el resultado, verifique que corresponda con su experiencia y realice los cambios que considere necesarios.

## Reflexión final

El desarrollo de esta página permite practicar cómo combinar estructura semántica y estilos para construir una interfaz con varias secciones. También muestra que una página visualmente organizada necesita pruebas en distintos tamaños y una revisión de accesibilidad y funcionalidad antes de considerarse terminada.