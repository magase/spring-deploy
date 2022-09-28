
## Despliegue de app Spring Boot en Heroku
Crear archivo `system.properties` en el proyecto con el contenido del runtime de java ->``java.runtime.verions=17``
1. Crear cuenta en heroku.com y en github.com
2. Tener configurado git en el ordenador:
   1. `git config --global user.name "Ram García"`
   2. `git config --global user.email "magase98@gmail.com"`
3. Subir proyecto a Github desde Intellij, tant con git como con VCS del IDE
4. Desde Herokum crear un app, elegir metodo GitHub y buscar el repositorio subido
5. Habilitar el deploy automatico y ejecutar el deploy