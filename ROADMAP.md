# Roadmap del Proyecto Top 50 Canciones Populares

Este documento describe las funcionalidades futuras y las mejoras planificadas para el proyecto del Top 50 de canciones populares de Instagram.

## Fase 1: Funcionalidades Base

* [ ] Mostrar una tabla con el título y autor de las 50 canciones más populares obtenidas de la API.
* [ ] Implementación del backend en Python Anywhere para interactuar con la API de Instagram utilizando un token de acceso seguro.
* [ ] Despliegue del frontend utilizando GitHub Pages.

## Fase 2: Mejoras de Seguridad y Backend

* [ ] **Refinamiento de la Seguridad del Token:** Asegurar que el token de acceso a la API de Meta se gestione de forma segura en el backend (utilización de variables de entorno, evitar logs, etc.).
* [ ] **Automatización de la Obtención de Datos:** Implementar una tarea programada en Python Anywhere para actualizar los datos del top 50 periódicamente, en lugar de solo bajo demanda del frontend.
* [ ] **Almacenamiento en Base de Datos (SQLite):** Introducir una base de datos SQLite en el backend para almacenar los datos del top 50. Esto permitirá un acceso más eficiente y la posibilidad de agregar funcionalidades futuras.

## Fase 3: Mejoras del Frontend

* [ ] **Estilos CSS:** Mejorar la apariencia de la tabla y la página web con estilos CSS personalizados.
* [ ] **Indicador de Carga:** Mostrar un indicador visual mientras se cargan los datos desde el backend.
* [ ] **Mensajes de Error:** Implementar mensajes de error más amigables en el frontend en caso de que falle la conexión con el backend o la obtención de datos.

## Fase 4: Funcionalidades Adicionales (Posibles)

* [ ] **Enlace** Mostrar un enlace a la cancion:
     * [ ] **v1) Enlace de búsqueda** de Google (Función).
     * [ ] **v2) Enlace al video** de Youtube (API).
* [ ] **Búsqueda y Filtrado:** Permitir a los usuarios buscar canciones o filtrar por autor dentro de la tabla.
* [ ] **Paginación:** Si usuarios reportan una mala experiencia, implementar paginación para no mostrar una tabla demasiado larga.
* [ ] **Detalles Adicionales:** Mostrar información adicional sobre cada canción (si la API lo proporciona).

## Consideraciones

* Este roadmap es flexible y puede cambiar según las necesidades y el tiempo disponible.
* Las prioridades de las fases y funcionalidades pueden ajustarse.
<!--* Se anima a la comunidad a proponer nuevas ideas y contribuir al proyecto.--->
