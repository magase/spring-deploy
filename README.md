
## Despliegue de app Spring Boot en Heroku
Crear archivo `system.properties` en el proyecto con el contenido del runtime de java ->``java.runtime.verions=17``
1. Crear cuenta en heroku.com y en github.com
2. Tener configurado git en el ordenador:
   1. `git config --global user.name "Ram García"`
   2. `git config --global user.email "magase98@gmail.com"`
3. Subir proyecto a Github desde Intellij, tant con git como con VCS del IDE
4. Desde Herokum crear un app, elegir metodo GitHub y buscar el repositorio subido
5. Habilitar el deploy automatico y ejecutar el deploy

## Ejercicio 1

* Probar a empaquetar la aplicación con maven package desde Intellij
* Desde la terminal verificar que se ejecuta correctamente el comando: 
```
java -version target/spring-deploy-1.0.jar
```
* Crear un perfil de dev y otro para test con una propiedad nueva que carguemos en el controlador.

## Ejercicio 2

* Desplegar el API REST de Laptops en Heroku y verificar su funcionamiento desde POSTMAN

## Proveedores Cloud
* Heroku -- Java, Spring, PostgreSQL...
* Netlify -- Frontend ( React, Angular... )
* Vercel -- Frontend ( React, Angular... ) 