# Comandos utilizados en el proyecto

## Crear Poyecto
```
composer create-project laravel/laravel nombre-del-proyecto 11.*
cd nombre-del-proyecto
```

## Paso 1
Configurar en el archivo .ENV conexion a la base de datos
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

## Paso 2
```
php artisan migrate
php artisan make:model Producto -m
php artisan make:controller ProductoController -r
```
En el archivo  **2025_04_01_025012_create_productos_table.php** definir campos de la tabla productos como ser: nombre, descripcion, precio, stock.

