## Despligue automático a Azure App Service

**William Ricardo Castañaza Romero**
**Carnet 0907-21-11816** 

# Descripción
Este proyecto consiste en una aplicación web simple desarrollada con Node.js y Express. Su objetivo principal es demostrar la configuración de un pipeline de despliegue continuo (CI/CD) utilizando GitHub Actions para desplegar automáticamente la aplicación en un Azure App Service.
Cada vez que se realiza un `push` a la rama `main`, el workflow se activa, compila el código (si es necesario) y lo despliega en la nube sin intervención manual.
