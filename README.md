# Proyecto Final de Desarrollo web Integrado
- Este proyecto fue realizado con fines de aprendizaje y aún faltan algunos aspectos visuales que deben pulirse. Sin embargo, la funcionalidad es a lo que más tiempo le hemos dedicado y consideramos que está en un estado óptimo.

## Integrantes:
- Samuel Elias Chipana Tito
- Yubert Omar Dueñas Cornejo
- Andrew Abdul Medina Warthon

## Instalación
- Crear la base de datos con el nombre "proyectolaravel" ubicado en la carpeta "Db" e importar el archivo "proyectolaravel.sql".

- Ejecutar el siguiente comando:
```bash
composer install
```

- Luego, copiar el archivo ".env.example" en el mismo directorio y renombrarlo a ".env".

- La configuración de este archivo debería quedar así:
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=proyectolaravel
DB_USERNAME=root
DB_PASSWORD=
```
- Ejecutar el siguiente comando para generar la clave de seguridad:

```bash
php artisan key generate
```

- Ejecutar el proyecto:
```bash
php artisan serve
```

## Notas
- En caso de querer una base de datos vacía contando únicamente con las tablas, crear la base de datos con el nombre "proyectolaravel" y ejecutar las migraciones:
```bash
php artisan migrate
```
 - Luego, ejecutar:
```bash
php artisan db:seed
```

## Créditos
- Este proyecto fue realizado utilizando como referencia el contenido del canal de YouTube [SakCode]
