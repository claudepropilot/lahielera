# La Hielera

Sitio estático de periodismo de investigación inspirado en xilografía centroamericana.

## Estructura

- `index.html`: portada con listado de investigaciones.
- `articulos.js`: manifiesto de investigaciones.
- `articulos/_plantilla.html`: plantilla para nuevos artículos.
- `articulos/nicaragua-juego-2026.html`: primer artículo publicado.

## Agregar un nuevo artículo

1. Copiar `articulos/_plantilla.html` a `articulos/nuevo-titulo-2026.html`.
2. Editar texto y contenido según la estructura establecida (mástera, ticker, secciones, referencias, pie).
3. Añadir entrada en `articulos.js` a la constante `ARTICULOS`:
   - `archivo`: nombre del archivo, sin `.html`.
   - `titulo`: título principal.
   - `bajada`: resumen breve.
   - `fecha`: formato `YYYY-MM-DD`.
   - `etiquetas`: array de etiquetas.
4. Abrir `index.html` y verificar despliegue.

## Ejecución

Abrir `index.html` en el navegador. No hay paso de construcción ni backend.

## Nota de estilos

- Colores: navy (#1a2354), red (#c0282d), cream (#f0e6d3), dark cream (#e0d4be).
- Tipos: Dela Gothic One, Archivo Black, Libre Baskerville, Special Elite.
- Textura: overlay con SVG `feTurbulence`.
