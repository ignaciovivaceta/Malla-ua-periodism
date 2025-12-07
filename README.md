[README.md](https://github.com/user-attachments/files/24017055/README.md)
# Malla Interactiva · Periodismo UA (2025)

Sitio estático listo para **GitHub Pages**. No requiere build ni dependencias (solo `index.html`).

## Cómo subir a GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `malla-periodismo-ua`).
2. Sube el archivo `index.html` a la raíz del repo.
3. Ve a **Settings → Pages** y en **Build and deployment** elige:
   - *Source*: **Deploy from a branch**
   - *Branch*: **main** (carpeta `/root`).
4. Guarda. La página quedará publicada en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Personalización
- Edita el bloque `const DATA = {...}` dentro de `index.html` para cambiar ramos, semestres, créditos, etc.
- Los filtros y el modal se actualizan automáticamente con los cambios del JSON.
