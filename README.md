# laravel-api

<a href="https://github.com/russsiq/laravel-docs-ru/">Русско язычная документация Laravel 9</a> <br/>
<a href="https://www.youtube.com/playlist?list=PLd2_Os8Cj3t8pnG4ubQemoqnTwf0VFEtU">Курс по Laravel</a> <br/>
<a href="https://www.code.mu/ru/php/framework/laravel/book/prime/">Учебник по Laravel</a>

### Запуск проект
cd project </br>
php artisan serve

### Задачи
1. Развернуть laravel
2. Интегрировать с БД MySQL
3. Разобраться с CORS, чтобы не мешал. Протестить dir (в ней dir-front, dir-laravel-api)
4. Разобраться с routers
5. Разобраться с resources

### Конечный результат шага 1

dir - laravel + MySQL + Data </br>

<b>Endpoints</b> </br>
api/users/ - (GET,POST,PUT,DELETE) + Pagination </br>
api/data/ - (GET,POST,PUT,DELETE) + Pagination </br>

Работа с шаблонизатором blade и вывод данных из MySQL

### Конечный результат шага 2

- oAuth - авторизация
- JWT либо другой пакет, для авторизации по токену для REST + SPA (Vue, React)

### Конечный результат шага 3

- Пакет для ролей пользователей
- Пакет для поиска на сайте
- Пакет email, рассылка

