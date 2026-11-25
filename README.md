# Inventario y Ganancias

App web de inventario, ventas y ganancias (RD$). Los datos se guardan en **Supabase** y la app se publica sola en **GitHub Pages** con cada cambio en `main`.

- `index.html`: toda la app.
- `.github/workflows/pages.yml`: publicación automática.

## Seguridad

La app entra directo, **sin inicio de sesión**. Todos los datos pertenecen a un único dueño compartido y cualquiera que tenga el enlace puede ver y modificar el inventario. La clave `sb_publishable_...` de `index.html` es pública por diseño.

Si más adelante quieres protegerla, se puede volver a añadir un inicio de sesión con Supabase Auth.

## Pasar tus datos antiguos

En la versión anterior (archivo local) usa **Descargar Respaldo (.json)**. Luego, en la app nueva, usa **Restaurar Respaldo (.json)**.

## Enlace

https://brahianyrd-ai.github.io/Inventario-y-Ganancias/
