
# ARQUITECTURA
## Arquitectura de desarrollo para el sistema jurídico 

# Patrón arquitectónico
-Este proyecto está pensado para ser construido bajo una arquitectura Cliente-servidor comunicada a través de una API RESTful.

-Escogí este modelo para separar la lógica de presentación (interfaz de usuario) de la lógica de negocio y acceso de datos, esto para que un futuro se pueda escalar la aplicación o desarrollar aplicaciones móviles tanto en ios como en Android 

# STACK TECNOLOGICO 
## BACKEND:

Para el backend se tiene pensado implementar java con el framework springboot, lo tomé como idea principal ya que al tratarse de un sistema legaltech se manejaran documentos de alta confidencialidad como expedientes legales, documentos públicos, datos personales de nuestros clientes y abogados, springboot ofrece un entorno altamente robusto, este maneja el ecosistema de springboot security esto para poder facilitar la autenticación y autorización basada en roles 

# FRONTEND:

Para el frontend se tiene pensado utilizar html5, css3 y javascript.                     Escogimos estas tecnologías web estándar para garantizar interfaces rápidas, ya que nuestro sistema no está basado en diseño y complejidad, por el contrario buscamos que el cliente tenga la mejor experiencia posible sin necesidad de saturar el diseño, javascript se encargara de consumir la api rest de manera asincrónica, brindando una experiencia fluida al usuario al momento de solicitar asesorías o cargar documentos sin la sobrecarga de aprender un framework desde cero, optimizando así los tiempos de carga. 

# BASE DE DATOS (MYSQL):

Nuestro sistema requiere una base de datos relacional debido a la naturaleza estructurada de la información, existe una fuerte relación entre las entidades de el sistema. MySQL garantiza la integridad referencial necesaria para que no haya inconsistencias en los historiales legales

# ALMACENAMIENTO DE ARCHIVOS:

En este entorno podríamos implementar tecnologías como Amazon S3, cloudinary o sistema de archivos esto ya dependerá de el entorno de despliegue que tengamos en cuenta. Esto se implementará ya que las bases de datos relacionales no están diseñadas para almacenar archivos pesados, dado que el sistema manejara documentos de dominio publico y expedientes, estos se almacenaran en un servicio de almacenamiento de objetos, en MySQL solo se guardara la URL o ruta de referencia al archivo optimizando el rendimiento de las consultas y reduciendo costos de base de datos.













