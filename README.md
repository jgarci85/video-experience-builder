# geoportal-miteco

Piezas auxiliares de la réplica del visor del Geoportal del MITECO en ArcGIS Experience Builder.

## reproductor.html

Reproductor de los vídeos de ayuda del Geoportal para las ventanas de la Experience.
Uso: `reproductor.html?v=<url del mp4>` (solo acepta vídeos de `https://sig.mapama.gob.es/`).

Experience Builder no desmonta una ventana al cerrarla, solo la oculta; esta página pausa
el vídeo en cuanto deja de verse, para que no siga sonando.
