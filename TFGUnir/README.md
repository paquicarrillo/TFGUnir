En este repositorio se encuentra todo el código utilizado durante el desarrollo de nuestro TFE, tanto para el despliegue de la infraestructura de herramientas como para el pipeline y el código de la aplicación usada como ejemplo para la simulación del despliegue de aplicaciones en distintos entornos

### cicd

Contiene el proyecto de GitLab con los pipelines plantillas y los ficheros de configuración necesarios para la ejecución del mismo.
## El directorio pipelines contiene el pipeline plantilla para despliegue de aplicaciones Sring Boot

### gitlab

Contiene el código para el despliegue usando contenedores Docker de la herramienta GitLab usada para el desarrollo del pipeline. 
Para desplegarlo, se descarga la carpeta a local y se ejecuta el comando docker-compose up -d desde el directorio donde se ha descargado el código.
Las instrucciones se encuentran detalladas en el documento del trabajo.

### holamundo

Contiene el código fuente de la aplicación ejemplo de Spring Boot que se usó como ejemplo en la ejecución del Pipeline.
Contiene además el pom.xml y el settings.xml (necesarios para la generación y almacenamiento de artefactos snapshot y release), docker-compose.yml (necesario para la ejecución en docker de la imagen Docker con artefacto) y el Dockerfile usado para la generación de la imagen con artefacto.
## El directorio src contiene el código de la aplicación y del test unitario.
## El directorio .m2 el settings.xml
## El directorio principal los archivos necesarios para la construcción de la imagen docker de la aplicación (Dockerfile) y el archivo para construcción y ejecución de contenedor docker-compose.xml.




