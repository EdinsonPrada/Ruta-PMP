# Ruta PMP

App web instalable para seguir el plan de estudio del examen PMP (temario ECO julio 2026).
Funciona sin conexión y guarda los datos solo en el dispositivo.

## Archivos

Todos van en la raíz del repositorio:

- `index.html` (la app completa)
- `manifest.webmanifest`
- `sw.js`
- `icon-180.png`, `icon-192.png`, `icon-512.png`

## Publicar en GitHub Pages

1. En github.com crea un repositorio público, por ejemplo `ruta-pmp`.
2. Add file > Upload files, sube los seis archivos y confirma con Commit changes.
3. Settings > Pages > Source: Deploy from a branch > Branch: `main`, carpeta `/ (root)` > Save.
4. Espera uno o dos minutos. La dirección será `https://TU-USUARIO.github.io/ruta-pmp/`.

## Instalar en el iPhone

1. Abre la dirección en Safari.
2. Compartir > Añadir a pantalla de inicio.
3. Abre la app desde el icono. Los datos viven en esa app instalada.

## Actualizar sin perder datos

1. Antes de actualizar: pestaña Apoyo > Copia de seguridad > Copiar, y guarda el texto en Notas.
2. Sube los archivos nuevos al mismo repositorio (reemplazan a los anteriores).
3. En `sw.js` el valor de `CACHE` debe cambiar en cada versión.
4. Abre la app con conexión; cierra y vuelve a abrir para ver la versión nueva.

Los datos se guardan bajo la clave `ruta-pmp-v2`; si venías de la versión 1 (`rutaPMP`) se convierten solos al abrir. No cambies la
dirección ni el nombre del repositorio: el almacenamiento está ligado a la dirección.
