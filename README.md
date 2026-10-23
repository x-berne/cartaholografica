# Carta Holográfica 3D (v1.0.0)

Efecto interactivo de carta coleccionable holográfica con inclinación 3D (tilt), reflejos de luz y patrón iridiscente optimizado para navegadores de escritorio y dispositivos móviles.

## Características

- **Efecto 3D y perspectiva:** Basado en `vanilla-tilt.js` con soporte para mouse y eventos táctiles (`touchmove`).
- **Patrón holográfico:** Gradientes y patrones con modos de fusión (`mix-blend-mode: plus-lighter` y `overlay`).
- **Optimizado para Mobile:** Textura de ruido estática acelerada por GPU para mantener 60/120 FPS sin ralentizaciones por filtros SVG dinámicos.
- **Bisel reflectante:** Borde metalizado con ángulo de refracción dinámico según la inclinación.
- **Script de renderizado cinemático:** Grabador de video automatizado (`record-option3.js`) usando Chrome DevTools Protocol y FFmpeg.

## Estructura del Proyecto

- `index.html`: Página principal con el diseño de la tarjeta, estilos CSS y lógica de inclinación.
- `vanilla-tilt.js`: Librería para el cálculo del efecto de inclinación 3D.
- `img.jpg`: Imagen de la carta.
- `record-option3.js`: Script de grabación en video automatizado.

## Uso

Abre `index.html` en cualquier navegador web o sírvelo localmente con cualquier servidor estático (como Live Server o `npx serve`).
