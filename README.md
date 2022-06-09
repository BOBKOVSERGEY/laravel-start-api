# Cоздание модели
php artisan make:model Task -mf

# Применить миграции
php artisan migrate

php artisan migrate:rollback

# Создание тестовых данных
php artisan make:seeder DeskSeeder

php artisan db:seed --class=TaskSeeder

# Создание контроллера для API
php artisan make:controller Api/DeskController --api

# Какие данные будем возвращать
php artisan make:resource DeskResource
