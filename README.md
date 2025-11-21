# Pagina2 — Perfil / Portfolio

**Descripción**
- **Sitio:** Página de perfil y portfolio creada con `pagina2.html`.
- **Contenido:** encabezado con menú, sección de perfil con imagen y habilidades, sección de álbumes (portfolio), formulario de contacto y pie de página.

**Archivos principales**
- `pagina2.html`: HTML principal del proyecto.
- `pagina2.css`: Hoja de estilos enlazada desde la página (asegúrate de que exista en la misma carpeta).
- `pruebas.css`: archivo CSS adicional presente en el repositorio (útil para pruebas de formulario/estilos).
- `pins/`: carpeta con imágenes usadas en la página.

**Cómo ver la página localmente**
- Opción rápida: abrir `pagina2.html` directamente en el navegador (doble clic).
- Servidor local (recomendado para rutas y carga de recursos): desde PowerShell, sitúate en la carpeta del proyecto y ejecuta:

```powershell
cd "c:\Users\PC-Core i5\Desktop\trabajos\desarrollo-web"; python -m http.server 8000
```

Luego abre en el navegador: `http://localhost:8000/pagina2.html`

**Dependencias**
- Ninguna. HTML/CSS puro (no requiere instalación de paquetes). Para recarga en caliente puedes usar la extensión Live Server de VS Code.

**Notas sobre los recursos**
- Asegúrate de que la carpeta `pins/` contenga las imágenes referenciadas desde `pagina2.html`. Si falta alguna imagen, reemplázala o actualiza las rutas en el HTML.
