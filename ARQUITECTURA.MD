
# ARQUITECTURA
## Arquitectura de desarrollo para el sistema jurídico 

# Patrón arquitectónico
-Este proyecto está pensado para ser construido bajo una arquitectura Cliente-servidor comunicada a través de una API RESTful.

-Escogí este modelo para separar la lógica de presentación (interfaz de usuario) de la lógica de negocio y acceso de datos, esto para que un futuro se pueda escalar la aplicación o desarrollar aplicaciones móviles tanto en ios como en Android 

# STACK TECNOLOGICO 
## BACKEND:

Para el backend se tiene pensado implementar java con el framework springboot, lo tomé como idea principal ya que al tratarse de un sistema legaltech se manejaran documentos de alta confidencialidad como expedientes legales, documentos públicos, datos personales de nuestros clientes y abogados, springboot ofrece un entorno altamente robusto, este maneja el ecosistema de springboot security esto para poder facilitar la autenticación y autorización basada en roles 


