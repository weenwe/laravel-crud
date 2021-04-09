# laravel-crud

### [Lihat Tutorial](https://www.wahyunanangwidodo.com/2021/04/tutorial-crud-laravel-8-mysql-database.html)

## Instalasi
```
git clone https://github.com/weenwe/laravel-crud.git
cd laravel-crud
composer install
php artisan key:generate
```
## Buat MySQL database
Silahkan buat database MySQL baru

## Buat file ```.env```
Rename file <b>.env.example</b> menjadi ```.env``` kemudian hubungkan database dengan mengaturnya pada bagian ```DB_DATABASE= ```
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_crud
DB_USERNAME=root
DB_PASSWORD=
```
## Jalankan migrasi tabel
```php artisan migrate```

## Jalankan aplikasi
```php artisan serve```
