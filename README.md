# Symfony blog-site + less

Стартовая заготовка для разработки блога.

Имеется готовая конфигурация doker. (Контейнеры: Nginx, MySql, Node, PHP).

Установлен Gulp и Less.

## Установка:
- клонируем репозиторий;
- в файле `.env` Задаем имя проекта `PROJECT_NAME=CREATE-NAME_project`;
- запускаем: `docker-compose up -d --build` (должен быть установлен [docker](https://www.docker.com/) и [docker-compose](https://docs.docker.com/compose/));
- переходим в директорию "app" и выполняем: `composer install` ([composer](https://getcomposer.org/download/) должен быть установлен);
- переходим в директорию `app/workflow`, выполняем: `npm i`. Должен быть установлен ([npm](https://www.npmjs.com/);
- запускаем приложение по адресу: [http://localhost](http://localhost). 