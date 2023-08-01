# API para NextStop: Encuentra gasolineras y puntos de recarga eléctricos en Cataluña


¡Bienvenido a la API para NextStop! Esta API es parte de la aplicación NextStop, una herramienta que te permite encontrar gasolineras y puntos de recarga eléctricos cercanos en el territorio de Cataluña. Además, podrás buscar estaciones en tus rutas personalizadas y explorar una red social donde puedes publicar reseñas sobre las estaciones de servicio.

## ¿Qué es NextStop?

NextStop es una aplicación desarrollada para ayudarte a encontrar las estaciones de servicio más cercanas en Cataluña, ya sea para cargar combustible tradicional o para recargar tu vehículo eléctrico. Con NextStop, podrás:

- Descubrir gasolineras y puntos de recarga eléctricos cercanos a tu ubicación actual.
- Planificar rutas personalizadas y encontrar estaciones en tu camino.
- Explorar y leer reseñas de otras personas sobre las estaciones de servicio.
- Mantenerte actualizado con información actualizada sobre las estaciones.

## Acerca de la API

Esta API ha sido desarrollada utilizando Spring Boot, un marco de trabajo de Java que facilita la creación de aplicaciones web y servicios RESTful. La API se conecta a una base de datos PostgreSQL, donde se almacenan y gestionan los datos sobre las estaciones de servicio en Cataluña.

### Obtención de datos

Los datos sobre las estaciones de servicio se obtienen cada 24 horas de una página web oficial del Estado Español, la cual proporciona la información en formato Excel. Estos datos se procesan automáticamente y se insertan en la base de datos para que estén disponibles para la aplicación NextStop.

### Swagger

Para facilitar el uso de la API, he implementado Swagger, una herramienta que te permite visualizar y probar los endpoints disponibles. Puedes acceder a la documentación de la API utilizando un navegador web y visitando la siguiente ruta: `/swagger-ui.html`. Allí encontrarás la lista de endpoints, la descripción de cada uno y los parámetros aceptados para realizar las solicitudes.

### Cómo obtener la imagen Docker

Si deseas utilizar la API y la base de datos en un entorno Docker, puedes obtener la imagen desde Docker Hub. La imagen contiene tanto la API de NextStop como una instancia de PgAdmin, lo que te permitirá gestionar la base de datos de manera visual.

Puedes obtener la imagen Docker en la siguiente URL de Docker Hub: [https://hub.docker.com/repository/docker/8aflow/nextstopapp/general](https://hub.docker.com/repository/docker/8aflow/nextstopapp/general)

## Contribuir

¡Estoy abierto a colaboraciones! Si deseas contribuir al desarrollo de la aplicación o informar sobre problemas, no dudes en crear un "issue" en el repositorio o enviar una solicitud de extracción (pull request).

