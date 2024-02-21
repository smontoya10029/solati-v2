1. creacion base de datos

   -- Database: solati

-- DROP DATABASE IF EXISTS solati;

CREATE DATABASE solati
    WITH
    OWNER = postgres
    ENCODING = 'UTF8'
    LC_COLLATE = 'Spanish_Colombia.1252'
    LC_CTYPE = 'Spanish_Colombia.1252'
    LOCALE_PROVIDER = 'libc'
    TABLESPACE = pg_default
    CONNECTION LIMIT = -1
    IS_TEMPLATE = False;

2. variables de conexion archivo env.

DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=solati
DB_USERNAME=postgres
DB_PASSWORD=prueba123

3. en la siguiente ruta se encuentra la migracion de la tabla:
   database/migration
   php artisan migrate

4. url donde correo el proyecto

   APP_URL=http://localhost:8000

