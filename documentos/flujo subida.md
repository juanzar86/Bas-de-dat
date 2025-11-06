# Flujo técnico de subida y despliegue del ecosistema BAS-NEO

## 1. Estructura base del proyecto

- Carpeta raíz: `site-base/`
- Archivos principales: `index.html`, `style.css`
- Carpeta de recursos: `assets/` → contiene `portada.png`
- Carpeta documental: `documents/` → contiene este archivo

## 2. Integración de portada institucional

- Imagen generada con título, autor y mentoría
- Guardada como `portada.png` en `assets/`
- Enlazada en `index.html` con:

```html
<img src="assets/portada.png" alt="Portada institucional BAS-NEO" width="600">
