# Awesome Project DB

Миграция схемы БД. В качестве БД используется *PostgreSQL*.

### Подготовка окружения:

```text
Экспортировать переменные окружения:
DB_URL - строка подключения к БД
DB_USER_NAME - имя пользователя БД
DB_USER_PASSWORD - пароль пользователя БД
```

### Создание/обновление схемы БД

```bash
gradle build update
```
