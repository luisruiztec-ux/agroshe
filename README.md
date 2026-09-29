# AGRO SHESED · Catálogo web (prototipo)

Proyecto estático listo para abrir en un navegador, subir a GitHub o desplegar en Vercel como sitio sin framework.

## Archivos

- `index.html`: estructura del catálogo.
- `styles.css`: estilos y diseño adaptable a celular.
- `app.js`: productos de ejemplo, búsqueda, filtros, WhatsApp y slider.
- `assets/logo-original.png`: logo entregado por la empresa.
- `assets/banner-1.svg` a `banner-3.svg`: escenas ilustrativas del slider.

## Personalización

1. En `app.js`, cambie `WHATSAPP='51999999999'` por el número comercial en formato internacional, sin `+` ni espacios.
2. Sustituya el arreglo `products` por los productos reales. Los actuales son demostrativos.
3. Cambie los archivos `assets/banner-*.svg` y sus referencias en `index.html` si dispone de fotos reales.
4. Actualice los textos de empresa y atención antes de publicar.

## Vista local

Abra `index.html` en el navegador. Si usa un servidor local: `python3 -m http.server 8000` y visite `http://localhost:8000`.

## Vercel

Suba esta carpeta a un repositorio GitHub. En Vercel, importe el repositorio y elija `Other` como framework; deje vacío el comando de build y publique el directorio raíz. Si coloca los archivos dentro de otra carpeta del repositorio, configúrela como Root Directory. La conexión con Supabase aún no forma parte de este prototipo.
