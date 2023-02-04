# template-laravel-with-docker
Template project laravel-9 with docker

* Из папки, в которой будет находиться проект, выполняем команды
```
git clone https://github.com/Kriodezz/template-laravel-with-docker.git .
composer install
```
*создаем в корне файл .env (копировать-вставить .env.example). В подключении к бд указываем
```
DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=root
```
