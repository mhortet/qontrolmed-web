# Estructura actual del sitio

## Paginas

### `index.html`

Portada principal con estas secciones:

- hero de presentacion
- bloque de producto
- bloque de solucion
- bloque de criterio visual
- llamada a contacto por email
- pie con enlaces principales

### `noticias.html`

Pagina para colgar informacion y novedades:

- cabecera editorial
- noticia destacada
- noticias secundarias
- barra lateral con categorias y contacto

## Estructura de carpetas

```text
qontrolmed-web/
|-- assets/
|   `-- img/
|-- css/
|   |-- base.css
|   |-- layout.css
|   |-- variables.css
|   `-- pages/
|       |-- home.css
|       `-- news.css
|-- docs/
|-- js/
|-- index.html
`-- noticias.html
```

## Criterios de crecimiento

- Mantener HTML estatico mientras el contenido siga siendo manejable
- Reutilizar layout y variables antes de crear estilos nuevos
- Crear una hoja CSS por pagina solo cuando haga falta
- Reservar `js/` para mejoras reales, no para inflar una web estatica
