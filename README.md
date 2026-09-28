# NOVOMART app

PWA interna de NOVOMART Creations. Estática, sin backend, sin dependencias.

## Qué incluye
- Botón "Hablar con Leo" (abre WhatsApp con Leo/Instinct).
- Accesos directos configurables (nombre + URL + emoji), guardados en localStorage del dispositivo.
- Sección Proyectos editable (nombre, estado, notas), en localStorage.
- Subida local de fotos/documentos: vista previa y reenvío con Web Share API; nada se sube a servidores.
- Instalable (manifest + service worker, caché offline). Marca: negro #18181a, dorado #c9a563.

## Deploy
GitHub Pages, rama `main`, raíz del repo. URL: https://alienbcn.github.io/novomart-app/

## Archivos
- `index.html` — app completa (HTML + CSS + JS inline).
- `manifest.webmanifest` — manifiesto PWA.
- `sw.js` — service worker (cache-first, offline).
- `icons/` — iconos 192/512/maskable/apple-touch/favicon.
