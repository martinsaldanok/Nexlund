# Nexlund: sitio en tres idiomas

Esta carpeta contiene los archivos terminados para publicar en GitHub Pages. Subí **el contenido de esta carpeta** a la raíz de la fuente de publicación de tu sitio (no la carpeta `nexlund-web` como tal).

| URL | Archivo |
| --- | --- |
| `https://nexlund.tech/` | `index.html` (alemán) |
| `https://nexlund.tech/es/` | `es/index.html` (español) |
| `https://nexlund.tech/en/` | `en/index.html` (inglés) |

**Importante:** conservá del repositorio actual `Images/Logo Nexlund.png`. El archivo pegado hacía referencia a ese logo, pero no lo incluía. Las tres páginas lo necesitan. Si tu logo tiene otro nombre o ubicación, cambiá la ruta `/Images/Logo Nexlund.png` en `assets/site.js` y en los tres HTML.

Las páginas usan un único `assets/site.js` y `assets/site.css`, más tres imágenes compartidas. Cada HTML contiene el contenido principal en su idioma para que pueda leerse sin esperar al JavaScript. Los enlaces de idioma llevan a URLs reales. Cada página declara su `lang`, título, descripción, canonical, `hreflang` y metadatos sociales. `sitemap.xml` y `robots.txt` señalan las tres URLs.

En GitHub: abrí el repositorio del sitio, elegí **Add file → Upload files**, arrastrá los archivos y carpetas que están dentro de `nexlund-web`, y confirmá con **Commit changes**. Reemplazá el `index.html` anterior. Verificá en **Settings → Pages** que la fuente de publicación sea la rama y carpeta donde los subiste. La opción habitual es `main` y `/(root)`; si tu sitio se publica desde `/docs` o `gh-pages`, subilos allí. En **Custom domain** debe figurar `nexlund.tech`; activá **Enforce HTTPS** cuando esté disponible. Si el dominio todavía no apunta a GitHub Pages, configurá los registros DNS siguiendo la documentación oficial de GitHub.

Después de la publicación, abrí las tres URLs y comprobá el logo, los enlaces de idioma y el botón de reserva. También podés enviar `https://nexlund.tech/sitemap.xml` a Google Search Console. El cambio de URLs puede tardar en reflejarse en los resultados de búsqueda.
