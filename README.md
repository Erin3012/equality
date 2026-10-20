# Equality Consultores

Sitio estático de Equality Consultores: portada con servicios, identidad, acreditaciones, clientes y contacto.

## Archivos

- `index.html`: página principal.
- `assets/`: recursos visuales.
- `.nojekyll`: permite servir los archivos directamente en GitHub Pages.

## Vista local

Abrir `index.html` en un navegador conservando la carpeta `assets` a su lado. No requiere instalación ni compilación.

## Fuentes

Contenido extraído de capturas de Instagram proporcionadas por el cliente. Fechas y precios antiguos no se presentan como oferta vigente. Los testimonios están identificados como publicaciones de 2022. Confirmar con Equality las condiciones de las próximas ediciones.


## Diseño actualizado

Portada basada en la referencia del cliente: encabezado diagonal, fotografía de obra, cinco áreas de servicios, identidad y propósito, alcance regional, acreditaciones, clientes y contacto. Los estilos están en `assets/site.css`. Se mantiene un sitio estático sin compilación y compatible con el despliegue existente de cPanel.

El menú móvil incluye cierre con Escape. Los enlaces de acreditaciones solicitan la documentación por correo; no se añaden certificados que no estén disponibles. Los nombres institucionales y de clientes son tratamientos tipográficos, no reproducciones de sus logotipos oficiales. Se conserva la resolución MOP indicada en el sitio original.

### Imágenes

- `assets/photos/hero.webp`: imagen ilustrativa generada con IA para esta portada.
- Fotografías de servicios: Unsplash, imágenes `photo-1454165804606-c3d57bc86b40`, `photo-1516321318423-f06f85e504b3`, `photo-1503387762-592deb58ef4e` y `photo-1581092921461-eab62e97a780`.
- `assets/photos/biobio.jpg`: Paul Edmonds (Conce), [Concepcion and the Biobio River](https://commons.wikimedia.org/wiki/File:Concepcion_and_the_Biobio_River.jpg), dominio público. Fotografía histórica utilizada como imagen regional.
- Logotipo de Equality: recurso existente del repositorio.

### Verificación

Revisado en navegador de escritorio y móvil: imágenes cargadas, ausencia de errores JavaScript y desbordamiento horizontal, menú móvil y cierre con Escape.


## Páginas individuales de servicios (propuesta 3)

Las cinco tarjetas de inicio abren las páginas de `servicios/`. Cada página incluye una portada fotográfica, áreas de trabajo, solicitud de propuesta por correo y navegación a los otros servicios. Los detalles no dependen de JavaScript. `assets/site.js` controla el menú móvil; `assets/servicios.css` contiene el diseño de las páginas individuales.

El texto completo de presentación e identidad de Edward se conserva en el desplegable de «Quiénes somos», con la presentación de Equality antes de la explicación del símbolo. Se mantienen los contactos y las acreditaciones existentes.

Las nuevas fotografías `planes-servicio.webp`, `formacion-servicio.webp` e `higiene-servicio.webp` son imágenes ilustrativas generadas con IA. Se sirven desde el propio sitio. La configuración `.cpanel.yml` despliega también la carpeta `servicios/`.

Validación: seis páginas y sus enlaces locales; navegación entre los cinco servicios; menú móvil, cierre con Escape y pantallas móviles de 390 y 320 px sin desbordamiento horizontal.
