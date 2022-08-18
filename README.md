## Despliegue de apps Spring Boot en Heroku

Crear arcivo 'system.properties' en el proyecto con el contenido:

---
java.runtime.version=18
---

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador
   1. git config --global user.name "Fabio ..."
   2. git config --global user.name "fabio@example.com"
3. Subir el proyecto a Github desde Intellij IDEA desde la opción: VCS > Share project on Github
4. Desde Heroku, crear app y elegir método Github y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el Deploy