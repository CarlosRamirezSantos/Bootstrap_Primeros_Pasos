# Bootstrap_Primeros_Pasos

Este README lista **todas las clases de Bootstrap detectadas en los archivos HTML del proyecto** y explica, de forma breve, qué hace cada una. La lista se ha generado a partir de los `class="..."` presentes en los HTML.

Nota sobre iconos: las clases `bi` y `bi-*` pertenecen a **Bootstrap Icons** (no al core de Bootstrap), y se usan para renderizar iconos.

## Layout y grid

| Clase | Qué hace |
| --- | --- |
| `container` | Contenedor con ancho fijo responsivo. |
| `container-fluid` | Contenedor a ancho completo. |
| `row` | Fila del sistema de grid. |
| `col` | Columna automática (ancho proporcional). |
| `col-12` | Columna que ocupa 12 columnas (100%). |
| `col-6` | Columna que ocupa 6 columnas (50%). |
| `col-md-3` | Columna 3/12 desde `md`. |
| `col-md-4` | Columna 4/12 desde `md`. |
| `col-md-6` | Columna 6/12 desde `md`. |
| `col-md-8` | Columna 8/12 desde `md`. |
| `col-md-12` | Columna 12/12 desde `md`. |
| `col-lg-2` | Columna 2/12 desde `lg`. |
| `col-lg-3` | Columna 3/12 desde `lg`. |
| `col-lg-4` | Columna 4/12 desde `lg`. |
| `col-lg-8` | Columna 8/12 desde `lg`. |
| `col-lg-9` | Columna 9/12 desde `lg`. |
| `row-cols-3` | Define 3 columnas por fila. |
| `row-cols-4` | Define 4 columnas por fila. |
| `g-2` | Gutter (espacio entre columnas) tamaño 2. |
| `g-3` | Gutter tamaño 3. |
| `g-4` | Gutter tamaño 4. |
| `gap-2` | Gap tamaño 2 para `flex`/`grid`. |
| `gap-4` | Gap tamaño 4 para `flex`/`grid`. |

## Display, flex y alineación

| Clase | Qué hace |
| --- | --- |
| `d-block` | Display block. |
| `d-inline` | Display inline. |
| `d-flex` | Display flex. |
| `d-grid` | Display grid. |
| `d-none` | Oculta el elemento. |
| `d-md-none` | Oculta desde `md`. |
| `d-md-block` | Muestra como block desde `md`. |
| `d-lg-none` | Oculta desde `lg`. |
| `d-lg-block` | Muestra como block desde `lg`. |
| `flex-row` | Dirección de flex en fila. |
| `flex-md-column` | Dirección de flex en columna desde `md`. |
| `flex-md-row-reverse` | Fila invertida desde `md`. |
| `flex-lg-row` | Dirección de flex en fila desde `lg`. |
| `justify-content-between` | Distribuye espacio entre items. |
| `align-items-start` | Alinea items al inicio en eje cruzado. |
| `align-items-center` | Alinea items al centro en eje cruzado. |
| `float-start` | Flota a la izquierda (inicio). |
| `float-end` | Flota a la derecha (fin). |

## Espaciado

| Clase | Qué hace |
| --- | --- |
| `m-1` | Margen en todos los lados (1). |
| `m-5` | Margen en todos los lados (5). |
| `mx-auto` | Margen horizontal automático (centrado). |
| `ms-auto` | Margen izquierdo automático. |
| `me-2` | Margen derecho (2). |
| `me-3` | Margen derecho (3). |
| `mt-1` | Margen superior (1). |
| `mt-2` | Margen superior (2). |
| `mt-3` | Margen superior (3). |
| `mt-4` | Margen superior (4). |
| `mt-5` | Margen superior (5). |
| `mb-2` | Margen inferior (2). |
| `mb-3` | Margen inferior (3). |
| `mb-4` | Margen inferior (4). |
| `mb-lg-0` | Margen inferior 0 desde `lg`. |
| `p-2` | Padding en todos los lados (2). |
| `p-3` | Padding en todos los lados (3). |
| `p-4` | Padding en todos los lados (4). |
| `pt-4` | Padding superior (4). |
| `pt-md-4` | Padding superior (4) desde `md`. |
| `pt-lg-0` | Padding superior 0 desde `lg`. |
| `py-4` | Padding vertical (4). |

## Tamaño y visibilidad

| Clase | Qué hace |
| --- | --- |
| `w-100` | Ancho 100%. |
| `w-25` | Ancho 25%. |
| `h-100` | Alto 100%. |
| `visually-hidden` | Oculto visualmente, accesible para lectores de pantalla. |

## Tipografía

| Clase | Qué hace |
| --- | --- |
| `h4` | Tamaño de encabezado `h4` aplicado como clase. |
| `h5` | Tamaño de encabezado `h5` aplicado como clase. |
| `h6` | Tamaño de encabezado `h6` aplicado como clase. |
| `small` | Tamaño de texto pequeño. |
| `fs-3` | Tamaño de fuente 3. |
| `fs-6` | Tamaño de fuente 6. |
| `fw-bold` | Texto en negrita. |
| `fst-italic` | Texto en cursiva. |
| `text-start` | Alinea texto a la izquierda. |
| `text-center` | Alinea texto al centro. |
| `text-end` | Alinea texto a la derecha. |
| `text-body` | Color de texto por defecto del body. |
| `text-muted` | Texto atenuado. |
| `text-black` | Texto negro. |
| `text-white` | Texto blanco. |
| `text-primary` | Color primario de texto. |
| `text-secondary` | Color secundario de texto. |
| `text-success` | Color de éxito para texto. |
| `text-danger` | Color de peligro para texto. |
| `text-warning` | Color de advertencia para texto. |
| `text-info` | Color de info para texto. |
| `text-light` | Texto claro. |
| `text-dark` | Texto oscuro. |
| `text-opacity-25` | Opacidad de texto 25%. |
| `text-opacity-50` | Opacidad de texto 50%. |
| `text-opacity-75` | Opacidad de texto 75%. |
| `text-opacity-100` | Opacidad de texto 100%. |

## Fondos y bordes

| Clase | Qué hace |
| --- | --- |
| `bg-primary` | Fondo con color primario. |
| `bg-secondary` | Fondo con color secundario. |
| `bg-success` | Fondo de éxito. |
| `bg-danger` | Fondo de peligro. |
| `bg-warning` | Fondo de advertencia. |
| `bg-info` | Fondo de info. |
| `bg-light` | Fondo claro. |
| `bg-dark` | Fondo oscuro. |
| `bg-black` | Fondo negro. |
| `border-primary` | Borde con color primario. |
| `border-success` | Borde con color éxito. |
| `border-warning` | Borde con color advertencia. |
| `border-info` | Borde con color info. |

## Posicionamiento y decoración

| Clase | Qué hace |
| --- | --- |
| `position-relative` | Posicionamiento relativo. |
| `position-absolute` | Posicionamiento absoluto. |
| `top-0` | Top 0. |
| `start-100` | Posiciona al 100% desde el inicio. |
| `translate-middle` | Traslada al 50% en ambos ejes. |
| `rounded` | Bordes redondeados. |
| `rounded-circle` | Bordes totalmente redondeados (círculo). |
| `rounded-pill` | Bordes tipo píldora. |
| `shadow-sm` | Sombra pequeña. |

## Imágenes

| Clase | Qué hace |
| --- | --- |
| `img-fluid` | Imagen responsiva (max-width: 100%). |
| `img-thumbnail` | Imagen con borde tipo thumbnail. |

## Tablas

| Clase | Qué hace |
| --- | --- |
| `table` | Tabla base de Bootstrap. |
| `table-striped` | Filas alternas con franjas. |
| `table-hover` | Resaltado al pasar el ratón. |
| `table-bordered` | Bordes en celdas. |
| `table-borderless` | Tabla sin bordes. |
| `table-sm` | Tabla compacta. |
| `table-dark` | Tabla con tema oscuro. |
| `table-primary` | Tabla con fila/celda primaria. |
| `table-active` | Estado activo para filas/celdas. |
| `table-responsive` | Tabla con scroll horizontal en pantallas pequeñas. |
| `caption-top` | Coloca el `caption` arriba. |

## Formularios

| Clase | Qué hace |
| --- | --- |
| `form-label` | Estilo para etiquetas de formulario. |
| `form-control` | Estilo base para inputs/textareas. |
| `form-control-color` | Estilo para input de tipo color. |
| `form-select` | Estilo base para selects. |
| `form-select-lg` | Select grande. |
| `form-check` | Contenedor de checkbox/radio. |
| `form-check-input` | Estilo para checkbox/radio. |
| `input-group` | Agrupa input con addons. |
| `input-group-text` | Texto/elemento en input group. |

## Botones

| Clase | Qué hace |
| --- | --- |
| `btn` | Botón base. |
| `btn-primary` | Botón primario. |
| `btn-secondary` | Botón secundario. |
| `btn-success` | Botón de éxito. |
| `btn-danger` | Botón de peligro. |
| `btn-warning` | Botón de advertencia. |
| `btn-info` | Botón de información. |
| `btn-light` | Botón claro. |
| `btn-link` | Botón con estilo de enlace. |
| `btn-outline-primary` | Botón contorno primario. |
| `btn-outline-secondary` | Botón contorno secundario. |
| `btn-outline-danger` | Botón contorno peligro. |
| `btn-sm` | Botón pequeño. |
| `btn-lg` | Botón grande. |
| `btn-group` | Agrupa botones en línea. |
| `btn-group-lg` | Grupo de botones grande. |
| `btn-group-vertical` | Grupo de botones vertical. |
| `btn-close` | Botón de cierre (X). |
| `btn-close-white` | Variante blanca del botón de cierre. |

## Alertas

| Clase | Qué hace |
| --- | --- |
| `alert` | Contenedor de alerta. |
| `alert-primary` | Alerta con color primario. |
| `alert-secondary` | Alerta con color secundario. |
| `alert-success` | Alerta de éxito. |
| `alert-link` | Estilo de enlace dentro de alert. |
| `alert-dismissible` | Permite cerrar la alerta. |

## Badges

| Clase | Qué hace |
| --- | --- |
| `badge` | Badge base. |
| `badge-light` | Badge con variante clara. |

## Breadcrumbs

| Clase | Qué hace |
| --- | --- |
| `breadcrumb` | Contenedor de migas de pan. |
| `breadcrumb-item` | Ítem de breadcrumb. |

## Cards

| Clase | Qué hace |
| --- | --- |
| `card` | Contenedor de card. |
| `card-header` | Cabecera de card. |
| `card-body` | Cuerpo de card. |
| `card-footer` | Pie de card. |
| `card-title` | Título de card. |
| `card-subtitle` | Subtítulo de card. |
| `card-text` | Texto de card. |
| `card-link` | Enlace en card. |
| `card-img` | Imagen de card (genérica). |
| `card-img-top` | Imagen en la parte superior. |
| `card-img-bottom` | Imagen en la parte inferior. |
| `card-img-overlay` | Contenido superpuesto a imagen. |
| `card-group` | Agrupa cards con el mismo alto. |

## Carousel

| Clase | Qué hace |
| --- | --- |
| `carousel` | Contenedor del carrusel. |
| `carousel-inner` | Contenedor interno de slides. |
| `carousel-item` | Slide individual. |
| `carousel-caption` | Texto superpuesto en el slide. |
| `carousel-indicators` | Indicadores del carrusel. |
| `carousel-control-prev` | Control para slide anterior. |
| `carousel-control-prev-icon` | Icono del control anterior. |
| `carousel-control-next` | Control para slide siguiente. |
| `carousel-control-next-icon` | Icono del control siguiente. |
| `carousel-fade` | Transición por desvanecimiento. |
| `slide` | Activa animación de deslizamiento. |

## Collapse y accordion

| Clase | Qué hace |
| --- | --- |
| `collapse` | Contenedor colapsable. |
| `collapse-horizontal` | Colapso horizontal. |
| `collapsed` | Estado inicial colapsado. |
| `show` | Estado mostrado (usado en collapse, dropdown, etc.). |
| `accordion` | Contenedor de acordeón. |
| `accordion-item` | Ítem del acordeón. |
| `accordion-header` | Cabecera del acordeón. |
| `accordion-button` | Botón del acordeón. |
| `accordion-collapse` | Sección colapsable del acordeón. |
| `accordion-body` | Cuerpo del acordeón. |

## Dropdown

| Clase | Qué hace |
| --- | --- |
| `dropdown` | Contenedor del dropdown. |
| `dropdown-toggle` | Botón/elemento que despliega el menú. |
| `dropdown-menu` | Menú desplegable. |
| `dropdown-item` | Ítem del menú. |
| `dropdown-header` | Cabecera dentro del menú. |
| `dropdown-divider` | Separador dentro del menú. |
| `fade` | Añade transición de opacidad. |

## Modal

| Clase | Qué hace |
| --- | --- |
| `modal` | Contenedor del modal. |
| `modal-dialog` | Caja del modal. |
| `modal-content` | Contenido del modal. |
| `modal-header` | Cabecera del modal. |
| `modal-body` | Cuerpo del modal. |
| `modal-footer` | Pie del modal. |
| `modal-title` | Título del modal. |
| `modal-lg` | Modal de tamaño grande. |

## Nav y navbar

| Clase | Qué hace |
| --- | --- |
| `nav` | Contenedor de navegación. |
| `nav-item` | Ítem de navegación. |
| `nav-link` | Enlace de navegación. |
| `nav-tabs` | Navegación con pestañas. |
| `active` | Marca elemento activo. |
| `navbar` | Barra de navegación. |
| `navbar-brand` | Marca/logo de la navbar. |
| `navbar-nav` | Lista de enlaces de la navbar. |
| `navbar-collapse` | Zona colapsable de la navbar. |
| `navbar-toggler` | Botón de colapso. |
| `navbar-toggler-icon` | Icono del botón de colapso. |
| `navbar-expand-lg` | Navbar expandida desde `lg`. |
| `navbar-light` | Tema claro para navbar. |
| `navbar-dark` | Tema oscuro para navbar. |

## Paginación

| Clase | Qué hace |
| --- | --- |
| `pagination` | Contenedor de paginación. |
| `page-item` | Ítem de paginación. |
| `page-link` | Enlace de paginación. |

## Listas

| Clase | Qué hace |
| --- | --- |
| `list-group` | Contenedor de list group. |
| `list-group-item` | Ítem del list group. |
| `list-group-item-action` | Ítem con comportamiento interactivo. |
| `list-group-flush` | List group sin bordes externos. |
| `list-inline` | Lista en línea. |
| `list-inline-item` | Ítem de lista en línea. |
| `list-unstyled` | Lista sin estilos (sin bullets). |

## Iconos (Bootstrap Icons)

| Clase | Qué hace |
| --- | --- |
| `bi` | Clase base para iconos de Bootstrap Icons. |
| `bi-check-lg` | Icono de check grande. |
| `bi-display` | Icono de display/pantalla. |
| `bi-phone` | Icono de teléfono. |
| `bi-search` | Icono de búsqueda. |
| `bi-star` | Icono de estrella. |
| `bi-star-fill` | Icono de estrella rellena. |
| `bi-star-half` | Icono de media estrella. |
| `bi-tablet` | Icono de tablet. |

## Clases no Bootstrap detectadas

Estas clases aparecen en los HTML, pero **no pertenecen a Bootstrap** o provienen de errores tipográficos en atributos `class`:

- `colores`
- `f`
- `=`
- `name=`

En `boostrap/11_Formularios.html` hay atributos `class` mal escritos (por ejemplo `class="form-control ="text"...` y `class="form-control name="descripcion"...`). Por eso aparecen `=` y `name=` como si fueran clases.
