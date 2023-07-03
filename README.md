Películas App

Películas App es una aplicación en Ruby on Rails que muestra películas, series y documentales. Permite agregar, listar y visualizar información sobre cada uno de estos ítems.

Requisitos

- Ruby (versión X.X.X)
- Rails (versión X.X.X)
- PostgreSQL (versión X.X.X)

Instalación

1. Clona el repositorio de Películas App:
   git clone https://github.com/tu-usuario/peliculas_app.git

2. Accede al directorio de la aplicación:
   cd peliculas_app

3. Instala las dependencias de Ruby:
   bundle install

4. Configura la base de datos en el archivo config/database.yml.

5. Crea la base de datos y ejecuta las migraciones:
   rails db:create
   rails db:migrate

6. Opcional: Si deseas agregar información de ejemplo, ejecuta las semillas:
   rails db:seed

7. Inicia el servidor de desarrollo:
   rails server

8. Accede a la aplicación en tu navegador web utilizando la dirección http://localhost:3000.

Uso

- En la página principal, podrás ver las películas, series y documentales agregados.
- Haz clic en el enlace "Agregar película", "Agregar serie" o "Agregar documental" para ingresar nueva información.
- Completa el formulario con los campos requeridos y haz clic en "Guardar".
- La nueva información se mostrará en la lista principal.

Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras algún error o tienes ideas para mejorar la aplicación, no dudes en abrir un issue o enviar un pull request.

Licencia

Este proyecto está bajo la Licencia MIT.
