# La Ciudad que Dormía — paquete GitHub con imágenes 3D

## Cómo subir
1. Descargá y descomprimí el ZIP.
2. Abrí tu repositorio `la-ciudad-que-dormia` en GitHub.
3. Elegí **Add file → Upload files** y arrastrá **el contenido** de esta carpeta (no el ZIP), incluyendo `imagenes/`.
4. Confirmá **Commit changes** y esperá la publicación de GitHub Pages.
5. Recargá la web con Ctrl+F5.

## Qué incluye
- 22 nodos narrativos, con 22 imágenes 3D asignadas desde `escenas-imagenes.js` (hay 27 imágenes WebP en total).
- Imágenes WebP de 1280 × 850 píxeles, comprimidas para la web, más SVG de respaldo. Son recortes ampliados de ilustraciones compuestas; no son renders nativos a 1280 × 850.
- Año 2087 en la historia y portada.
- Botón Comenzar misión, decisiones, volver, reiniciar, narración por voz del navegador, sonidos y modo proyector.
- Configuración del chat VERA hacia `https://vera-nova-arcadia.araxfourth.workers.dev`. **No se comprobó aquí que el Worker/Gemini respondan correctamente**; el Worker requiere su secret `GEMINI_API_KEY` y `ALLOWED_ORIGIN` correcto.

## Importante
- `worker-gemini.js` es referencia para Cloudflare y no se ejecuta en GitHub Pages. No subas claves API.
- Si el chat falla, revisá Cloudflare Worker y consola del navegador; la narración depende de las voces disponibles en el equipo.
- No se modificó el contenido narrativo original salvo mantener el año 2087 que ya estaba en esta versión.
