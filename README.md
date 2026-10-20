# Katherinne Núñez — Sitio web

Sitio estático (HTML/CSS/JS), sin build ni dependencias.

## Archivos
- `index.html`: página principal, con los flujos de Asesoría 1:1, reality y branding.
- `preparacion.html`: formulario previo a la llamada; al terminar muestra la agenda.
- `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`: íconos.
- `.nojekyll`: evita que GitHub Pages procese el sitio con Jekyll.

## Publicar en GitHub Pages
1. Crea un repositorio y sube todos estos archivos a la raíz.
2. Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)`.
3. Para usar tu dominio, agrega un archivo `CNAME` con el dominio dentro y configura el DNS.

## Servicios conectados
- **Supabase**: tabla `leads` (Asesoría 1:1), tabla `previa_llamada` y bucket `insights`.
- **Splitforms**: envío de correos.
Las claves de `index.html` y `preparacion.html` son las públicas (publishable). Nunca pongas la `service_role`.
