# Stained Glass Deck — editor para GitHub Pages

Editor estático para personalizar cada una de las 40 cartas (8 pintas × Joker, A, J, Q y K). Permite subir una ilustración propia por carta, ajustar tamaño, posición y opacidad, combinarla con el marco vectorial y exportar SVG/PNG o las 40 cartas en un ZIP.

## Publicar
1. Descomprime el ZIP y sube el contenido de esta carpeta a la raíz de tu repositorio.
2. En GitHub abre Settings → Pages.
3. Elige Deploy from a branch, `main` y `/(root)`.

## Cómo usar las referencias
- Selecciona una carta en la galería.
- En “Ilustración propia” elige un PNG/JPG/WebP/SVG. La imagen se incrusta en la carta y se exporta dentro del SVG.
- Ajusta tamaño, opacidad y ubicación. Desmarca “Mantener ornamentación vectorial” si quieres dejar solo la imagen y el marco exterior.
- Exporta el ZIP para descargar los 40 SVG, o guarda el proyecto JSON para respaldo y para trasladar las imágenes/ajustes a otro navegador.

## Persistencia
El editor guarda automáticamente en localStorage del navegador. Como las imágenes ocupan espacio, exporta periódicamente el proyecto JSON. El ZIP masivo requiere conexión para cargar JSZip desde CDN. Google Fonts es opcional y solo afecta la tipografía del panel, no la estructura de las cartas.

## Nota sobre las pintas
Los símbolos y paletas son provisionales. Puedes reemplazarlos en el arreglo `SUITS` de `app.js` por las ocho pintas definitivas.
