<h1>BookCatalog</h1>

## Установка и настройка среды

- [Скачать и установить PHP](https://www.php.net/downloads.php)
- [Скачать и установить XAMPP](https://www.apachefriends.org/index.html) (среда разработки PHP)
- [Скачать и установить NodeJS](https://nodejs.org/en/) (фреймворк JavaScript) 
- [Скачать и установить Composer](https://getcomposer.org/) (PHP dependency manager) 
- Скачать и установить Laravel (в терминале: ```composer global require laravel/installer```)
- [Скачать ZIP-архив проекта BookCatalog и разархивировать](https://github.com/bekezh/bookcatalog/archive/refs/heads/master.zip).

## Активация проекта в локальной сети

- Открыть XAMPP и запустить Apache Web Server и MySQL Database <br>
(***Проверить работу XAMPP можно перейдя по ссылке:*** ```http://localhost```)
- Разархивировать ZIP-архив BookCatalog
- Перейти в phpMyAdmin
```http://localhost/phpmyadmin```
- Создать базу данных **bookcatalog**
- Переименовать файл ```.env.example``` на ```.env```
- Открыть папку проекта в терминале
- Написать следующую команду
```php artisan serve```
- Перейти по следующей ссылке в браузере
```http://localhost:8000/products```
