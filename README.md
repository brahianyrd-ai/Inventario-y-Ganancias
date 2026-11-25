# Inventario y Ganancias

App web de inventario, ventas y ganancias (RD$). Los datos se guardan en **Supabase** (con inicio de sesión) y la app se publica sola en **GitHub Pages** con cada cambio en `main`.

- `index.html`: toda la app.
- `.github/workflows/pages.yml`: publicación automática.

## Seguridad

La clave `sb_publishable_...` en `index.html` es pública por diseño. Los datos quedan protegidos por Row Level Security: cada usuario solo ve y modifica sus propias filas.

## Pasar tus datos antiguos

En la versión anterior (archivo local) usa **Descargar Respaldo (.json)**. Luego, ya con sesión iniciada aquí, usa **Restaurar Respaldo (.json)**.

## Enlace

https://brahianyrd-ai.github.io/Inventario-y-Ganancias/
