# Ritual Virtual · Psicogato

## 🎮 Jugar ahora

**[Abrir Ritual Virtual · Psicogato](https://mrtronch.github.io/RitualVirtual2DGame/)**

Disponible desde el navegador en computadora, celular y tablet.

Juego estático listo para publicar. Sube **todo el contenido de esta carpeta**, conservando `index.html` y `assets/` juntos. No requiere compilación ni servicios de backend.

## Probar
Abre `index.html`, o sirve esta carpeta con `python -m http.server 8000` y abre `http://localhost:8000`. Para móvil, abre la dirección del sitio publicado. También puedes servirlo en tu red local.

## Controles
- Flechas izquierda/derecha o A/D: mover. Flecha arriba: saltar o salto de pared.
- Abajo/S: agacharse. Mantener J y soltar: disparar (máximo a 1,5 s).
- K: zarpazo. L: dash. Espacio o botón Pausa: detener/continuar.
- Móvil: joystick analógico a la izquierda y botones en rombo: salto abajo, dash a la derecha, disparo a la izquierda y zarpazo arriba; pausa en el centro. Puedes mantener dirección y disparo simultáneamente. En vertical los controles quedan debajo del escenario; en horizontal se superponen. Menú y juego conservan el mismo tamaño de imagen.

## Sonido y mando
Los siete audios están optimizados en MP3 dentro de `assets/`. Las músicas del nivel, boss y puntaje se repiten en sus respectivas pantallas y respetan sus controles de volumen. Play se reproduce una vez antes de iniciar el nivel. Opciones incluye volúmenes independientes para efectos y música. Pulsa START para activar el mando; stick/cruceta navegan los menús, botón inferior confirma y derecho vuelve.

## Diálogos editables
Edita `Dialogo nivel 1.txt` en el proyecto principal, manteniendo los encabezados EVENTO 1/2/3 y los nombres de personaje antes de los dos puntos. Ejecuta `Actualizar-juego.cmd` y vuelve a subir index.html y assets. La copia en `editor/` es una referencia editable; la web usa los diálogos ya compilados. Enter, J, toque o botón inferior del mando revelan el texto o avanzan.

## Puntaje
Al completar el nivel aparece un contador animado de 0 al resultado, con un máximo de 9999. El tiempo aporta hasta 7000 puntos; enemigos hasta 1800, ítems hasta 699 y completar el nivel 500. Cada golpe descuenta 35 y cada vida perdida 350. Las pausas y diálogos no consumen tiempo de puntuación. Las ratas invocadas no permiten acumular puntos ilimitados. El resultado todavía no se envía a un servidor.

## Mapa editable
`editor/outputs/tiled/nivel-01.tmj` incluye los conjuntos externos y sus imágenes. Se conserva la estructura de rutas para abrirlo en Tiled. Los cambios del editor deben recompilarse desde el proyecto principal antes de volver a exportar esta carpeta.

El exportador separa las imágenes del HTML para facilitar la subida. `assets/` contiene todos los recursos usados por esta versión. No se ha publicado ni subido nada a una cuenta remota.
