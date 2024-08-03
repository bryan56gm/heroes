# Proyecto de Gestión de Superhéroes con MySQL

Este es un proyecto de aplicación web simple para gestionar una lista de superhéroes utilizando una base de datos MySQL. La base de datos se puede crear e importar a través de phpMyAdmin.

## Descripción

La aplicación permite a los usuarios:

- **Ver la lista de superhéroes**: Consultar una lista de superhéroes almacenada en la base de datos.
- **Agregar nuevos superhéroes**: Añadir nuevos superhéroes a la base de datos.
- **Editar superhéroes existentes**: Modificar la información de superhéroes existentes.
- **Eliminar superhéroes**: Borrar superhéroes de la base de datos.

## Requisitos

- Servidor web con soporte para PHP y MySQL (e.g., WAMPServer)
- phpMyAdmin para la gestión de la base de datos

## Instalación y Ejecución

1. **Descarga e instala WAMPServer:**
   - Recomendado WAMPServer para esta guia.
   - Sigue las instrucciones de instalación y asegúrate de que esté ejecutándose.

2. **Clona el repositorio en la carpeta `www` de WAMPServer:**
   ```bash
   cd C:\wamp64\www
   git clone https://github.com/bryan56gm/heroes.git
   cd tu_proyecto

3. **Clona el repositorio en la carpeta `www` de WAMPServer:**
   Crea la base de datos en phpMyAdmin:

   - Abre tu navegador y ve a http://localhost/phpmyadmin.
   - Inicia sesión con el usuario root (sin contraseña).
   - Haz clic en la pestaña "Importar".
   - Selecciona el archivo SQL proporcionado con el proyecto (e.g., superheroes.sql) y cárgalo para crear la base de datos y las tablas necesarias.
