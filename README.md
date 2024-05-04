<style>
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

h1, h2, h3, h4, h5 {
  color: #C7BCFF;
}

h1 {
  border-bottom: 2px solid #333;
  padding-bottom: 5px;
}

code {
  background-color: #f4f4f4;
  padding: 2px 4px;
  border-radius: 4px;
}

pre {
  background-color: #f8f8f8;
  padding: 10px;
  border-radius: 5px;
  overflow-x: auto;
}

ul, ol {
  margin-bottom: 10px;
}

a {
  color: #007bff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>


# Proyecto de Gestión de Productos con Flask y SQLite3

Este proyecto consiste en una aplicación web desarrollada en Python utilizando el framework Flask y una base de datos SQLite3 para gestionar los datos de distintos productos.

## Funcionalidades

- **Base de Datos SQLite3:** La aplicación utiliza una base de datos en SQLite3 para almacenar los datos de los distintos productos.
  
- **Python y Flask:** Se trabaja con Python como lenguaje de programación y Flask como framework web para el desarrollo de la aplicación.

- **Templates:**
  - **base.html:** Template base que se extiende por las distintas vistas de la aplicación.
  - **index.html:** Muestra en una tabla los productos guardados en la base de datos y permite redirigir al detalle de cada producto al dar click en el nombre.
  - **producto.html:** Template que muestra el detalle de un producto específico y permite regresar a la vista principal.

## Requisitos

- Python 3.x
- Flask
- SQLite3

## Instalación

1. Clona este repositorio en tu máquina local.
2. Crea un entorno virtual (opcional pero recomendado).
3. Instala las dependencias del proyecto:

- pip install flask

4. Ejecuta la aplicación:

- python main.py

5. Abre tu navegador y visita `http://localhost:5000` para ver la aplicación en funcionamiento.

## Estructura del Proyecto

- **main.py:** Archivo principal que contiene la lógica de la aplicación Flask.
- **templates/:** Carpeta que contiene los templates HTML de la aplicación.
- **base.html**
- **index.html**
- **producto.html**
- **static/:** Carpeta para archivos estáticos como CSS, fotos, imágenes, etc.
