# laravel-crud
## Instalasi
```
1. git clone https://github.com/weenwe/laravel-crud.git
2. cd laravel-crud
3. composer install
4. ren .env.example .env (ubah nama file env.example menjadi .env)
5. php artisan key:generate
```
## Atur Database
```
//.env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_crud
DB_USERNAME=root
DB_PASSWORD=
```
## Jalankan Migrasi Tabel
```php artisan migrate```

## Jalankan Aplikasi
```php artisan serve```

## Pembahasan
### [Tutorial CRUD Laravel 8 - MySQL Database](https://www.wahyunanangwidodo.com/2021/04/tutorial-crud-laravel-8-mysql-database.html)
