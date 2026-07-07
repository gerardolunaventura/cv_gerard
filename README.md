# CV — Gerardo Luna Ventura

Sitio de una sola página (`index.html`, sin dependencias externas más allá de Google Fonts)
listo para publicarse con **GitHub Pages**.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (público), por ejemplo `gerardo-cv`.
2. Sube este archivo `index.html` a la raíz del repositorio (rama `main`).
   ```bash
   git init
   git add index.html README.md
   git commit -m "CV inicial"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/gerardo-cv.git
   git push -u origin main
   ```
3. En GitHub, ve a **Settings → Pages**.
4. En "Build and deployment", selecciona **Deploy from a branch**, rama `main`, carpeta `/root`.
5. Guarda. En 1-2 minutos tu CV estará publicado en:
   `https://TU_USUARIO.github.io/gerardo-cv/`

## Antes de publicar, personaliza:

- **LinkedIn / GitHub**: reemplaza los `href="#"` en la sección de contacto (hay dos: hero y footer) por tus perfiles reales.
- **Métricas de automatización con IA**: el bullet marcado con *"(agrega aquí tu métrica real...)"* en Experiencia debe reemplazarse por un número concreto tuyo (ej. "-30% en tiempo de ejecución de regresión", "120 casos de prueba automatizados"). Los reclutadores valoran mucho más una cifra real que una frase genérica.
- **Herramientas de IA específicas**: en "Habilidades técnicas" se listan ejemplos genéricos (generación de casos con IA, testing visual con IA). Sustitúyelos por las herramientas exactas que usaste (Copilot, ChatGPT, Testim, Mabl, Applitools Eyes, etc.) para que el CV sea 100% preciso.
- **Botón "Descargar CV"**: usa `window.print()` (imprime/exporta a PDF desde el navegador). Ya incluye una hoja de estilos de impresión limpia — solo prueba con Ctrl/Cmd+P para verificar que se vea bien antes de compartir el link.

## Estructura

```
index.html   → todo el sitio (HTML + CSS + JS en un solo archivo)
README.md    → este archivo
```

Sin build steps, sin frameworks — cualquier cambio de texto es editar directamente el HTML.
