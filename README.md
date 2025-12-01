# Ciberseguridad · Recurso educativo

Este proyecto contiene una página estática en español pensada para el alumnado de 4.º de ESO de la asignatura de Digitalización. Incluye una introducción a la ciberseguridad, consejos de protección y un catálogo de ataques basado en la guía del INCIBE.

## Uso

1. Clona el repositorio y asegúrate de que la carpeta `assets/` se mantiene (contiene los SVG usados en la página).
2. Coloca tu imagen de portada en `assets/portada-ciberseguridad.png` (el archivo está en `.gitignore` para evitar errores de carga en la PR).
3. Abre `index.html` en tu navegador para ver la web con todos los recursos locales cargados.
4. Si quieres servirla con un servidor estático, puedes usar por ejemplo:
   ```bash
   python -m http.server 8000
   ```
   y visitar `http://localhost:8000`.

Las ilustraciones SVG están versionadas en el repositorio. La portada en PNG debes aportarla localmente para que aparezca en la cabecera.
