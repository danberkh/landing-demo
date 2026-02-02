# Landing Page Demo

Este es un proyecto simple de Landing Page diseñado para ser hosteado fácilmente en **GitHub Pages**.

## Estructura de Archivos

El proyecto sigue una estructura estándar:

```text
landing-demo/
├── index.html          # Tu página principal
├── assets/
│   ├── css/
│   │   └── style.css   # Estilos visuales (Tema oscuro premium)
│   └── js/
│       └── main.js     # Interactividad (Menú móvil)
└── README.md           # Este archivo
```

## Cómo probarlo localmente

Simplemente abre el archivo `index.html` en tu navegador web (Chrome, Firefox, Safari, etc.). No se requiere instalación de servidores ni dependencias (Node.js, Python, etc.) ya que está hecho con HTML, CSS y JS puro.

## Cómo subirlo a GitHub Pages

1.  Crea un nuevo repositorio en GitHub (ej: `mi-landing-page`).
2.  Sube todos los archivos de la carpeta `landing-demo` a ese repositorio.
    *   Asegúrate de que `index.html` esté en la raíz del repositorio.
3.  En GitHub, ve a **Settings** (Configuración) del repositorio.
4.  En el menú lateral, busca la sección **Pages**.
5.  En **Build and deployment** > **Source**, selecciona `Deploy from a branch`.
6.  En **Branch**, selecciona `main` (o `master`) y la carpeta `/ (root)`.
7.  Haz clic en **Save**.

¡Listo! En unos minutos GitHub te dará el link público de tu sitio.

## Personalización

-   **Cambiar colores**: Edita las variables CSS en `assets/css/style.css` (al principio del archivo).
-   **Editar textos**: Modifica directamente el archivo `index.html`.
