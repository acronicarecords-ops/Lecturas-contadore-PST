# Lecturas de Contadores — Puerto Sotogrande

App móvil (Android e iOS) para anotar las lecturas de electricidad y agua de cada atraque, organizada en pestañas por zonas, con exportación a PDF A4 y opción de compartir.

## Archivos
- `index.html` — la app completa (diseño, fuentes y lógica incluidos).
- `manifest.json` — permite instalarla en la pantalla de inicio.
- `sw.js` — permite abrirla sin conexión (red primero, caché como respaldo).
- `icon-192.png`, `icon-512.png` — iconos de la app.

## Publicar con GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.

Las lecturas se guardan en el propio móvil (almacenamiento local del navegador).
