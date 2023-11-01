# Informes | Asamblea Regional

Este es el repositorio del sitio web "Informes | Asamblea Regional", diseñado para la Asamblea Regional 2023 en San Juan, con el tema "Tengan Paciencia". El sitio web proporciona informes y recursos para el evento. A continuación, encontrarás información sobre la estructura del proyecto y cómo funciona.

Puedes visitar el sitio haciendo clic aquí: [Asamblea Regional](https://guillosgit.github.io/AsambleaRegional/index.html)


## Contenido del Repositorio

- `index.html`: El archivo HTML principal que define la estructura de la página web.
- `assets/`: Directorio que contiene los archivos de activos, como imágenes y hojas de estilo.
  - `SVG/`: Contiene el archivo de icono del sitio web.
  - `styles.css`: Archivo CSS personalizado para estilos adicionales.
- `data/`: Directorio que almacena datos en formato JSON.
  - `data.json`: Archivo JSON que contiene información sobre las categorías y enlaces del sitio web.
- `README.md`: El archivo que estás leyendo ahora, que proporciona información sobre el proyecto.

## Cómo funciona el sitio web

El sitio web se basa en HTML y utiliza Bootstrap para la maquetación y estilos. También carga datos desde un archivo JSON para crear enlaces a diferentes categorías. A continuación, se describen las partes clave del sitio web:

- **Barra de navegación**: La barra de navegación en la parte superior de la página contiene información sobre el departamento y la asamblea regional.

- **Cuerpo de la página**: El cuerpo de la página contiene un contenedor de tarjetas donde se mostrarán enlaces a diferentes categorías.

- **Funcionalidad JavaScript**: Se utiliza JavaScript para cargar y mostrar los datos desde el archivo JSON. La función `fetchData` se encarga de obtener los datos y, luego, la función `createCategoryCards` crea tarjetas para cada categoría y las muestra en la página.

## Cómo utilizar el proyecto

Para utilizar este proyecto, simplemente sigue estos pasos:

1. Clona este repositorio en tu sistema local.

2. Abre el archivo `index.html` en tu navegador web para ver el sitio web en acción.

3. Si deseas personalizar el contenido del sitio web o agregar más categorías, puedes editar el archivo `data/data.json` con tus propios datos.

4. Puedes modificar los estilos del sitio web editando el archivo `assets/styles.css`.

## Recursos Externos

- [Bootstrap](https://getbootstrap.com/docs/5.2): Se utiliza Bootstrap para la maquetación y estilos del sitio web.

Esperamos que este README te ayude a comprender y trabajar con el sitio web "Informes | Asamblea Regional". ¡Disfruta personalizando y compartiendo este sitio web para tu evento!
