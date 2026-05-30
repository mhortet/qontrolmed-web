# QontrolMed Web

Base web estatica para presentar QontrolMed con una portada corporativa,
contacto por email y una pagina de noticias preparada para crecer.

## Estructura actual

- `index.html`: portada de producto con propuesta de valor, solucion y contacto.
- `noticias.html`: espacio para novedades, publicaciones y avisos.
- `css/variables.css`: tokens visuales comunes.
- `css/base.css`: reset y estilos base.
- `css/layout.css`: componentes compartidos y estructura global.
- `css/pages/`: estilos especificos por pagina.
- `assets/img/`: logotipo e imagenes del sitio.

## Ver en local

Con VS Code y Live Server:

1. Abrir `index.html`.
2. Ejecutar `Open with Live Server`.
3. Revisar tambien `noticias.html`.

Sin extensiones, tambien sirve abrir los HTML directamente en navegador.

## Plan de trabajo

1. Ordenar carpetas y estilos.
2. Dejar una landing corporativa bien cerrada.
3. Preparar futuras paginas como `servicios.html`, `contacto.html` y `sobre-qontrolmed.html`.
4. Valorar mas adelante una migracion a Astro o Vite si el sitio crece.

Por ahora tiene sentido mantener HTML + CSS sin frameworks para ir rapido,
con menos complejidad y una base facil de mantener.

## Siguiente fase recomendable

- Definir mensajes finales del producto.
- Sustituir noticias de ejemplo por contenido real.
- Decidir futuras paginas: servicios, casos de uso, sobre la empresa.
- Valorar mas adelante migracion a Astro o Vite si el sitio crece.
