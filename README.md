# Movies Exporer (Frontend)

## Описание
Многостраничное адаптивное приложение, предназначенное для поиска фильмов по ключевому слову, в качестве базы данных используется API Яндекса.

На данном проекте отработала навыки подключения фронтенда к 2 базам данных (API Яндекса с фильмами и моей базе пользователей на MongoDB), различные сценарии взаимодействия пользователя с многостраничным сайтом на React, включая обработку ошибок и сообщения о них.

## Функциональность
1. Поиск фильмов по ключевому слову с подключением к базе API Яндекса.
2. Подгрузка фильмов по клику на кнопку "Ещё" (видимость кнопки и количество подгружаемых фильмов зависят от разрешения экрана).
3. Сохранение и удаление фильмов из избранного.
4. Фильтрация фильмов по параметру длительности.
5. Переход на внешний трейлер по клику на превью фильма.
6. Регистрация и авторизация пользователя.
7. Изменение данных пользователя (имя и e-mail).

## Стек
1. JavaScript
2. React
3. Webpack
4. HTML
5. CSS

## Ссылки
1. [Приложение](https://movies-explorer.vaal.nomoredomains.icu/)
2. [Макет в Figma](https://disk.yandex.ru/d/MGa0iE0HLZAqDA)

## Инструкция по развёртыванию
```
git clone https://github.com/ValLugovaia/movies-explorer-frontend.git
cd movies-explorer-frontend
npm install
```

## Планы по доработке
1. Переписать приложение на TypeScript.