# BackEquipo2

Este proyecto es un backend desarrollado en [Laravel](https://laravel.com/), y surge como resultado de un curso universitario sobre este framework de PHP. El sistema puede ser utilizado como base para practicar desarrollo web con Laravel y comprender los fundamentos de la creación de APIs y aplicaciones orientadas a bases de datos.

## Características

- Estructura siguiendo buenas prácticas de Laravel.
- Uso de rutas, controladores y modelos para manejar la lógica de la aplicación.
- Plantillas Blade para la vista (si aplica).
- Integración con base de datos mediante Eloquent ORM.

## Requisitos

- PHP >= 8.0
- [Composer](https://getcomposer.org/)
- Laravel 10.x o superior (ajustar según versión usada)
- Servidor de base de datos MySQL/MariaDB/PostgreSQL

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/Javiguapo/BackEquipo2.git
    cd BackEquipo2
    ```

2. Instala las dependencias:
    ```bash
    composer install
    ```

3. Copia el archivo de ejemplo de variables de entorno y edítalo según tus datos de base de datos:
    ```bash
    cp .env.example .env
    # Edita el archivo .env con tus credenciales (DB_DATABASE, DB_USERNAME, DB_PASSWORD, etc.)
    ```

4. Genera la clave de aplicación de Laravel:
    ```bash
    php artisan key:generate
    ```

5. Realiza las migraciones para crear las tablas en la base de datos:
    ```bash
    php artisan migrate
    ```

6. Levanta el servidor de desarrollo:
    ```bash
    php artisan serve
    ```

7. Accede a la app en [http://localhost:8000](http://localhost:8000)

## Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras un error o deseas mejorar este proyecto, abre un issue o envía un pull request.

## Autor

JavierGonzL
https://github.com/JavisGL

## Licencia

Este proyecto está bajo la licencia MIT.
