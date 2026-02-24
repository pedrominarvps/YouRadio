# YouRadio

Página estática para GitHub Pages con 2 vistas:

1. **Inicio (`index.html`)** estilo portada para pegar el enlace.
2. **Reproductor (`player.html`)** estilo cinematográfico Astral, con fondo dinámico, carrusel sincronizado, barra de progreso interactiva y controles avanzados (shuffle, seek ±10s, mute, anterior/siguiente).

## Flujo

1. Pegas un URL de un video musical en la portada.
2. La app redirige al reproductor.
3. Se reproduce automáticamente y se genera la cola recomendada.
4. En “Próximas canciones” se muestran títulos y puedes hacer clic para cambiar de canción.
5. Debajo del reproductor tienes acciones rápidas: Descargar video (YTDown), Descargar Musica y Ventana flotante.
6. El carrusel se expande automáticamente con más de 200 canciones (modo continuo).

## Publicar en GitHub Pages

- Sube `index.html` y `player.html` al repositorio.
- En GitHub, activa **Settings → Pages** y selecciona la rama principal.
- Abre la URL pública de Pages, pega un enlace en la portada y entrarás al reproductor.
