# Portafolio profesional — Maximiliano Abascal

Este repositorio contiene una página estática (HTML/CSS/JS) pensada para mostrar tu perfil profesional, experiencia y proyectos. Es responsive, editable localmente y lista para desplegar en Vercel (Hobby).

Archivos principales
- [index.html](index.html#L1) — Página principal (contenido inicial en español).
- [styles.css](styles.css#L1) — Estilos globales.
- [assets/CV-Maximiliano-Abascal.txt](assets/CV-Maximiliano-Abascal.txt#L1) — CV descargable en texto.
- [assets/avatar.svg](assets/avatar.svg#L1) — Avatar simple.

Editar contenido
- La página carga datos iniciales desde el propio `index.html` (objeto `initialData`).
- Para edición rápida en el navegador: presiona el botón ⚙ (panel inferior) para abrir el panel de administración y agregar/editar proyectos y experiencias. Los cambios se guardan en el `localStorage` del navegador (persisten en ese equipo/navegador).
- Para cambios permanentes (en el repositorio): edita `index.html` y/o `assets/CV-Maximiliano-Abascal.txt` y haz commit.

Despliegue en Vercel (Hobby)
1. Crea un repositorio en GitHub y sube estos archivos.
2. Inicia sesión en https://vercel.com y conecta tu repositorio. Vercel detecta un sitio estático y desplegará automáticamente.

Alternativa: usar la CLI de Vercel

```bash
npm i -g vercel
vercel login
cd /ruta/al/proyecto
vercel --prod
```

Notas
- El panel admin guarda datos en `localStorage`. Para que los cambios estén disponibles desde cualquier dispositivo, edítalos en el repositorio.
- Evité integraciones de servidor (formularios, bases de datos) para mantener compatibilidad con el plan Hobby de Vercel.

Si quieres, puedo:
- Añadir soporte para múltiples idiomas (ES/EN) y cambiar el contenido dinámicamente.
- Generar un PDF del CV y añadirlo como archivo descargable.
- Subir al repositorio y configurar Vercel por ti (necesitaré acceso al repo o instrucciones).
