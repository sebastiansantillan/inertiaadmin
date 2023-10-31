# Velvet Inertia Admin

Panel de administración para Laravel + Vue3 + Tailwind con Inertia3. Incluye soporte Typescript.

## Stack

- Laravel 10.x
- Inertia3-Vue
- Vue3

## Instalación y configuración

1. Clonar el repositorio en local con el nombre que va a tener el proyecto:

```sh
git clone https://github.com/sebastiansantillan/inertiaadmin.git nombredelproyecto
```

2. Acceder al directorio:

```sh
cd nombre del proyecto
```

3. Copiar el archivo `.env.example` como `.env` y ajustar las variables de entorno.

4. Instalar librerías y ejecutar migraciones

```sh
composer update
php artisan migrate
php artisan key:generate
npm install
```
