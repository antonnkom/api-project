# Тестовое REST-API приложение с собственными mock-данными.

## Используемые технологии
1. Node.js
2. TypeScript
3. JSON

## Установка

```bash
npm install
```

## Запуск GET-запроса в браузере

```bash
node --loader ts-node/esm comments-api.ts
```

1. После запуска скрипта и сообщения ***Server running on port 3000*** открыть страницу [http://localhost:3000/api/comments](http://localhost:3000/api/comments)

## Запуск POST-запроса

Для запуска POST и GET запросов использовалась программа [Postman](https://www.postman.com/downloads/)

Тело POST запроса:

```json
[
    {
        "title": "Smartphone",
        "price": 19900,
        "category": "Smartphones"
    },
    {
        "title": "Smartphone",
        "price": 24900,
        "category": "Smartphones"
    }
]
```
