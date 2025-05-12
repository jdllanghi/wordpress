# Práctica Servidor Web

## 1. Título

**Despliegue de un entorno WordPress usando Docker Compose con servicios de MySQL y phpMyAdmin**

## 2. Tiempo de duración

**120 minutos**

## 3. Fundamentos

Docker es una plataforma de contenedores que permite crear, desplegar y ejecutar aplicaciones en entornos aislados y consistentes. En esta práctica se utilizará **Docker Compose**, una herramienta que facilita la gestión de múltiples contenedores usando archivos de configuración en formato YAML.

WordPress es un sistema de gestión de contenido (CMS) muy utilizado para la creación de sitios web. Funciona con un backend basado en PHP y requiere una base de datos MySQL. phpMyAdmin es una herramienta web que permite gestionar bases de datos MySQL de forma gráfica.

Para lograr esta práctica, se deben entender varios conceptos clave:

- **Contenedores**: unidades ligeras y portables que contienen todo lo necesario para ejecutar una aplicación.
- **Servicios en Compose**: cada contenedor definido en el archivo `docker-compose.yml` representa un servicio.
- **Redes**: permiten que los contenedores se comuniquen entre sí de forma interna.
- **Volúmenes**: se usan para persistir datos incluso si el contenedor se reinicia o elimina.



## 4. Conocimientos previos

Para realizar esta práctica el estudiante necesita tener claro los siguientes temas:

- Comandos básicos de Linux.
- Uso de terminal o consola.
- Manejo básico de navegadores web.
- Conceptos fundamentales de bases de datos (MySQL).
- Conocimiento previo de Docker y su sintaxis.

## 5. Objetivos a alcanzar

- Implementar contenedores de WordPress, MySQL y phpMyAdmin utilizando Docker Compose.
- Definir redes y volúmenes persistentes en el archivo `docker-compose.yml`.
- Manipular archivos de configuración en formato YAML.
- Validar la comunicación entre los servicios definidos.

## 6. Equipo necesario

- Computador con sistema operativo **Windows**, **Linux** o **macOS**.
- Acceso a terminal con permisos de administrador.
- Cuenta en [https://labs.play-with-docker.com/](https://labs.play-with-docker.com/) o Docker Desktop.
- **Docker v24.0.0** o superior.
- Editor de texto (Visual Studio Code, nano, etc.).

## 7. Material de apoyo

- Documentación oficial de Docker: https://docs.docker.com/
- Guía de la asignatura.
- Linux Command Cheat Sheet: https://files.fosswire.com/2007/08/fwunixref.pdf
- Documentación de Docker Compose: https://docs.docker.com/compose/

## 8. Procedimiento


## Paso 1: Crear una carpeta para tu proyecto
- Creamos la carpeta para wordpress
<img src="paso 1.png" alt="Paso2" width="800">
<img src="paso (1.1).png" alt="Paso2" width="800">


## Paso 2: Crear el archivo docker-compose.yml
- En este paso describimos el archivo yml
<img src="paso 2.png" alt="Paso2" width="800">

## Paso 3: Levantar los servicios
- Aqui vemos si docker esta corriendo 
<img src="paso 3.png" alt="Paso2" width="800">

## Paso 4: Acceder a los servicios
- Comprobamos que los puertos esten corriendo 
- WordPress: http://localhost:8080

- pgAdmin: http://localhost:8081

<img src="paso 4.png" alt="Paso2" width="800">
<img src="paso (4.1).png" alt="Paso2" width="800">

## 9. Resultados esperados
- Se espera que el servicio de WordPress sea accesible desde el navegador en el puerto 8080 y que permita completar su instalación.
- pgAdmin debe estar disponible en el puerto 8081, mostrando la base de datos wordpress creada por PostgreSQL.
- Los servicios deben estar funcionando simultáneamente, demostrando el uso eficiente de contenedores.

## 10. Bibliografía
- Docker. (n.d.). Docker Documentation. https://docs.docker.com
- PostgreSQL Global Development Group. (n.d.). PostgreSQL Documentation. https://www.postgresql.org/docs/
- WordPress Foundation. (n.d.). WordPress.org. https://wordpress.org
- dPage. (n.d.). pgAdmin Documentation. https://www.pgadmin.org/docs/
