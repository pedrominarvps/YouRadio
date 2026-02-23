# YouRadio

Página estática para GitHub Pages que convierte un enlace de YouTube en una "radio" automática, con fondo dinámico del video en reproducción:

1. Pegas un URL de un video musical.
2. Se reproduce automáticamente.
3. Se genera una cola de canciones recomendadas y se reproducen una tras otra.
4. En “Próximas canciones” se muestran títulos y puedes hacer clic para cambiar de canción.
5. Debajo del reproductor tienes acciones rápidas: Descargar video (YTDown), Descargar Musica y Ventana flotante.

## Publicar en GitHub Pages

- Sube `index.html` al repositorio.
- En GitHub, activa **Settings → Pages** y selecciona la rama principal.
- Abre la URL pública de Pages y pega un enlace de YouTube.

## Nota técnica

La app usa la mezcla automática de YouTube (`RD<videoId>`) para construir una radio basada en recomendaciones reales de la plataforma.
No requiere API Key de Google, por lo que funciona bien en GitHub Pages como sitio estático.
