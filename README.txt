Landspire Studio — sitio completo
=================================

Estructura
- index.html .......................... Página principal de Landspire
- img/ ................................ Imágenes de la página principal
- samples/alder-pine-dental/ .......... Muestra: Alder & Pine Dental (implantes, Austin)
- samples/brightline-orthodontics/ .... Muestra: Brightline Orthodontics (Invisalign, Denver)
- samples/lark-linen-aesthetics/ ...... Muestra: Lark & Linen Aesthetics (Botox y piel, Chicago)

Las páginas están conectadas con rutas relativas: las cards de "Sample work"
abren cada muestra y el botón de regreso de cada muestra vuelve a la sección
de muestras de la página principal.

Publicar en Cloudflare Pages
1. Cloudflare > Workers & Pages > Create > Pages > Upload assets.
2. Arrastra el contenido de esta carpeta (o el zip).
3. Conecta tu dominio landspirestudio.com en Custom domains.

Las URLs quedarán así:
- https://landspirestudio.com/
- https://landspirestudio.com/samples/alder-pine-dental/
- https://landspirestudio.com/samples/brightline-orthodontics/
- https://landspirestudio.com/samples/lark-linen-aesthetics/

Pendiente: los formularios (muestra gratis en Landspire y los de las
muestras) aún no envían datos a ningún lado.
