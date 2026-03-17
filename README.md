# Hola Mundo en PHP

#Descripción
Este es un proyecto introductorio diseñado para la clase de Fundamentos de Construcción de Software, enfocado en la configuración de un entorno de servidor web local en Linux (Ubuntu y la integración de diferentes tecnologías web.

El proyecto consiste en una página web que muestra un mensaje de bienvenida personlizado utilizando PHP.
El diseño incluye una imagen generada mediante inteligencia artificial con la herramienta Leonardo AI, representando el concepto de ingeniería de software.

#Prerrequisitos
Para ejecutar este proyecto en un entorno local Linux, es necesario contar con lo siguiente:
1. Servidor Web (Apache): El intérprete para servir páginas web.
   * Comando de instalación: sudo apt update && sudo apt install apache2
2. Intérprete de PHP: Necesario para ejecutar el código del lado del servidor.
   * Comando de instalación: sudo apt install php
   * libapache2-mod-php
3. Permisos de carpeta: Es vital configura los permisos correctos en el directorio del servidor para poder crear y guardar archivos.
   * Comando utilizado: sudo chmod
   * 775 /var/www/html -R

#Pasos para su ejecución
1. Ubicación de archivos: Mueve los archivos dep proyecto a la carpeta del servidor web: /var/www/html/proyecto php/
2. Encender el servidor: Asegúrate de que Apache esté funcionando con el siguiente comando: sudo systemctl start apache2
3. Visualización en navegador: Abre tu navegador web dentro de la máquina virtual y accede a la siguiente direción: http://localhost/proyecto%20php/index.php

4. #Datos del autor
5. Nombre: Kateryn Guarcas
6. Correo:26006042@galileo.edu
