# Ritual Virtual · Psicogato

Juego estático listo para publicar. Sube **todo el contenido de esta carpeta**, conservando `index.html` y `assets/` juntos. No requiere compilación ni servicios de backend.

## Probar
Abre `index.html`, o sirve esta carpeta con `python -m http.server 8000` y abre `http://localhost:8000`. Para móvil, abre la dirección del sitio publicado. También puedes servirlo en tu red local.

## Controles
- Flechas izquierda/derecha o A/D: mover. Flecha arriba: saltar o salto de pared.
- Abajo/S: agacharse. Mantener J y soltar: disparar (máximo a 1,5 s).
- K: zarpazo. L: dash. Espacio o botón Pausa: detener/continuar.
- Móvil: controles táctiles para dirección, salto, carga de disparo, dash, zarpazo y pausa. Puedes mantener dirección y disparo simultáneamente. Recomendado en horizontal.

## Mapa editable
`editor/outputs/tiled/nivel-01.tmj` incluye los conjuntos externos y sus imágenes. Se conserva la estructura de rutas para abrirlo en Tiled. Los cambios del editor deben recompilarse desde el proyecto principal antes de volver a exportar esta carpeta.

El exportador separa las imágenes del HTML para facilitar la subida. `assets/` contiene todos los recursos usados por esta versión. No se ha publicado ni subido nada a una cuenta remota.
