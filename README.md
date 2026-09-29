# Sitio de SKOIS

Páginas públicas de las aplicaciones de SKOIS, servidas con GitHub Pages.

    /                          SKOIS y la lista de apps
    /launcher/                 SKOIS Launcher Minimalist
    /launcher/privacidad.html  su política de privacidad
    estilo.css                 hoja compartida por todas las páginas

Sin generadores ni dependencias: son ficheros HTML sueltos. Para verlo en
local basta con `python -m http.server` desde esta carpeta.

## Añadir otra aplicación

1. Copia `launcher/` a una carpeta nueva y cambia sus textos.
2. Añade una tarjeta `<li>` en `index.html`.

La política de privacidad de cada app vive en su propia carpeta: Google Play
pide una URL por aplicación.
