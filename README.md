 Scraping de Propiedades de Alquiler en Infocasas

Este proyecto realiza un web scraping de propiedades de alquiler en Montevideo desde el sitio web [Infocasas](https://www.infocasas.com.uy). El objetivo es extraer información detallada sobre apartamentos disponibles para alquilar, como el título, la URL, la imagen, el precio y la ubicación, y luego guardar estos datos en un archivo Excel.

## Descripción

El script recorre varias páginas de la sección de alquileres de Infocasas y extrae la siguiente información de cada propiedad listada:

- **Título del proyecto**: El nombre del apartamento.
- **URL**: El enlace directo a la página del apartamento.
- **Imagen**: URL de la imagen principal del apartamento.
- **Precio**: El precio de alquiler de la propiedad.
- **Ubicación**: La ubicación del apartamento en Montevideo.
- **Tipo**: El tipo de propiedad (en este caso, "Alquiler UY").

## Requisitos

Antes de ejecutar el script, asegúrate de tener instaladas las siguientes dependencias:

- `requests`: Para realizar las solicitudes HTTP al sitio web.
- `BeautifulSoup`: Para parsear y extraer datos del HTML.
- `pandas`: Para almacenar y manipular los datos.
- `openpyxl`: Para guardar los datos en un archivo Excel.

Puedes instalar las dependencias con:

```bash
pip install requests beautifulsoup4 pandas openpyxl
