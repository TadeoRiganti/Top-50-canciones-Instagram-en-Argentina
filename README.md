# Top 50 Canciones · Instagram (Argentina)

Este proyecto es una página web sencilla que muestra el top 50 de canciones populares de Instagram. Los datos se obtienen a través de una API y se visualizan en una tabla HTML.

## Funcionalidades Actuales

* Muestra una tabla con el top 50 de canciones.
* Cada fila de la tabla incluye el título de la canción y el autor.
* Los datos se obtienen dinámicamente desde un backend.

## Tecnologías Utilizadas

* **Frontend:** HTML, CSS, JavaScript (Vainilla).
* **Backend:** Python (Flask).
* **Servidor Frontend:** GitHub Pages (para servir los archivos estáticos HTML y JavaScript).
* **Servidor Backend:** Python Anywhere (para la lógica de la API y la comunicación con la API de Instagram).

## Arquitectura

1.  El frontend (ejecutándose en GitHub Pages) utiliza JavaScript para hacer una petición HTTP al backend.
2.  El backend (ejecutándose en Python Anywhere) recibe la petición.
3.  El backend (utilizando un token de acceso seguro) llama a la API de Instagram para obtener el top 50 de canciones en formato JSON.
4.  El backend procesa el JSON, extrayendo la información relevante (título y autor).
5.  El backend responde al frontend con un JSON que contiene la lista de canciones y sus autores.
6.  El JavaScript en el frontend recibe el JSON y manipula el DOM para crear y llenar la tabla HTML con los datos de las canciones.

<!-- ## Configuración

Si quieres ejecutar este proyecto localmente (solo el frontend, ya que el backend requiere Python Anywhere):

1.  Clona este repositorio:
    ```bash
    git clone [https://github.com/delulu?tab=repositories](https://github.com/delulu?tab=repositories)
    cd [nombre del repositorio]
    ```
2.  Abre el archivo `index.html` en tu navegador.

**Nota:** Para que la obtención de datos funcione, el backend en Python Anywhere debe estar configurado y ejecutándose con un token de acceso válido a la API de [Nombre de tu Red Social]. --->

## Despliegue

El frontend de este proyecto se despliega automáticamente utilizando [GitHub Pages](https://pages.github.com/).

El backend debe configurarse y desplegarse manualmente en [Python Anywhere](https://www.pythonanywhere.com/).

## Próximos Pasos (Roadmap)

Ver el archivo `ROADMAP.md` para conocer las futuras funcionalidades y mejoras planificadas.

<!-- ## Contribución

Las contribuciones son bienvenidas. Por favor, revisa las [guías de contribución](CONTRIBUTING.md) (si las creas) para obtener más información sobre cómo puedes ayudar. --->

## Licencia

MIT Licensce
