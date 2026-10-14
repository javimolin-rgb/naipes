# Mazo Stained Glass — editor y exportador

Editor visual estático con estética de vitral: contornos oscuros tipo plomo, paneles geométricos, paletas saturadas y motivos ornamentales.

## Publicar en GitHub Pages
1. Descomprime el ZIP.
2. Sube `index.html` a la raíz de un repositorio de GitHub (este proyecto está en un solo archivo, por simplicidad).
3. En el repositorio, entra a **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
5. Guarda y espera la URL de GitHub Pages.

## Funciones
- 8 pintas de ejemplo y 5 cartas por pinta: Joker, As, J, Q y K (40 cartas).
- Edición en vivo de colores, símbolo, título, motivo y detalle.
- Motivos: bufón, sol, luna, flor, ave, ojo, corona y llama.
- Exportación de la carta actual a SVG o PNG de 1500 × 2500.
- Guardar/cargar configuración JSON.
- Exportación de las 40 cartas como ZIP con SVG individuales.

## Importante sobre las pintas
Los nombres/símbolos concretos del enlace que compartiste antes no están disponibles en el contexto actual que pude recuperar. Por eso las ocho pintas están como ejemplos provisionales. Puedes sustituir nombre, símbolo y colores en el arreglo `suits` dentro del `index.html`.

La exportación masiva usa JSZip desde CDN, así que requiere conexión a internet al pulsar el botón. El editor y la exportación individual SVG funcionan sin esa librería.
