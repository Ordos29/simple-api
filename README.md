### Simple API

Подготовка БД

```
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate --no-interaction
```

Методы API

* Список пользователей: `GET /users`
* Получить пользователя: `GET /users/1`
* Добавить пользователя: `POST /users`
* Удалить пользователя: `DELETE /users/1`

* Получить профиль пользователя: `GET /users/1/profile`
* Обновить профиль пользователя: `PUT /users1/profile`
