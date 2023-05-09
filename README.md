# MVC, MySql, y Docker

Este repositorio es una prueba técnica para desarrolladores en Laravel, MySql, y Docker. A continuación se presentan las tareas a realizar para completar la prueba.

## Tareas

### MySql
1. Crear una base de datos llamada `BDPrueba`.
2. Crear las siguientes tablas en la base de datos:
   * Productos
   * Facturas
   * Detalle Facturas

### Laravel
1. Crear procedimientos almacenados para insertar, actualizar y eliminar datos de las tablas utilizando su propia lógica de programación.
2. Desarrollar un proyecto MVC con Laravel en Visual Studio CODE que permita controlar las tablas con la base de datos creada.
3. Utilizar las siguientes características de Laravel:
   * Clases
   * Vistas
   * Base de datos
4. El nombre del proyecto debe ser `PruebaInterface`.

### Docker
1. Crear un archivo `docker-compose.yml` que incluya las siguientes imágenes:
   * `gumadesarrollo/php:7.4-apache-sqlsrv-prod` como imagen de referencia para PHP.
   * Nginx
   * MySql
2. Configurar el archivo `docker-compose.yml` para que el proyecto Laravel se ejecute en el puerto 80.
3. Configurar el archivo `docker-compose.yml` para que la base de datos MySql use el puerto 3306.
4. Crear un archivo `.env` que contenga la información de conexión a la base de datos MySql.

### GIT
1. Hacer un Fork de este repositorio.
2. Crear varios commits que muestren el progreso del desarrollo.
3. Enviar un Pull Request a la Branch `developer` cuando se complete la prueba.

## Instrucciones adicionales
- Utilice las versiones más recientes de Laravel, MySql y Docker.
- Es importante incluir comentarios explicativos en el código.
- La estructura de las tablas y los procedimientos almacenados son flexibles, puede diseñarlos según crea necesario.
- Se espera que el código sea limpio y fácil de entender.
- Siéntase libre de agregar cualquier característica adicional que considere útil para completar la prueba.
