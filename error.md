# Ошибки

Пример ответа об ошибке:

```json
{"jsonrpc": "2.0", "error": {"code": 123, "message": "Post not found"}, "id": "1"}
```

У параметра `error` есть два обязательных аттрибута: `code` и `message`,
и один необязательный: `data`.
