En este repositorio se encuentra todo el código utilizado tanto para el despliegue de la infraestructura, el pipeline y el código de la aplicación usada como ejemplo para la simulación
del despliegue de aplicaciones en distintos entornos

### cicd

Contiene el proyecto de GitLab con los pipelines plantillas y los ficheros de configuración necesarios para la ejecución del mismo.

### gitlab

Contiene el código para el despliegue usando contenedores Docker la herramienta usada para el desarrollo del pipeline GitLab
Para desplegarlo, se descarga la carpeta a local y se ejecuta el comando docker-compose up -d.
Las instrucciones se encuentran detalladas en el documento del trabajo

### holamundo

Contiene el código fuente de la aplicación ejemplo de Spring Boot que se usó como ejemplo en la ejecución del Pipeline.
Contiene además el pom.xml (necesario para la generación y almacenamiento de artefactos snapshot y release), Docker-compose.yml (necesario para la ejecución en docker de la imagen Docker con artefacto)
y el Dockerfile usado para la generación de la imagen con artefacto




