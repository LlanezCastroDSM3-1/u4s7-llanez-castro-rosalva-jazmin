# U4S7-llanez-castro-rosalva-jazmin

## Demo en vivo (producción)
https://u4s7-llanez-castro-rosalva-jazminonrender.com

## Semana 7 — Pulido funcional, UX y simulacro de defensa
En esta entrega de la Unidad 4 - Semana 7 se realizaron las siguientes mejoras y pulidos sobre el proyecto integrador:

* **Paginación:** Se implementó `Paginator` en la vista de servicios para agrupar los registros en páginas de 5 elementos.
* **Búsqueda simple:** Se añadió un formulario con método GET para filtrar los servicios por título usando `icontains`.
* **Estados vacíos:** Se configuró la etiqueta `{% empty %}` en la plantilla para mostrar mensajes claros e intencionales cuando no existen registros o la búsqueda no arroja resultados.
* **Persistencia de búsqueda y paginación:** Los controles de paginación mantienen el parámetro `?q=` al cambiar de página.
* **UI Review & Accesibilidad:** Se revisó la interfaz en pantalla móvil (~375px) con desplazamiento horizontal en tablas (`overflow-x-auto`) y etiquetas `aria-label` en controles.

### Hallazgos de la UI review corregidos:
1. "Se ajustó el contraste del texto en encabezados secundarios."
2.  "Se añadieron atributos aria-label al buscador para lectores de pantalla."