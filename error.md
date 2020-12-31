# Ошибки

Пример ответа об ошибке:

```json
{"jsonrpc": "2.0", "error": {"code": 123, "message": "Post not found"}, "id": "1"}
```

У параметра `error` есть атрибуты:

* `code` - код ошибки (обязательный)
* `message` - краткое описание ошибки (обязательный)
* `data` - дополнительные данные об ошибке (необязательный)

## Код ошибки

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

### Ошибка разбора

* Код - -32700
* Описание - Сервер получил недействительный JSON. На сервере произошла ошибка при разборе текста JSON.

### Ошибка разбора



* Неподдерживаемая кодировка.
* /
const UNSUPPORTED_ENCODING = -32701;

### 

/ **
* Ошибка разбора
* Неверный символ для кодировки.
* /
const INVALID_CHARACTER_FOR_ENCODING = -32702;

### 

/**
* Server error
* Invalid Request
* The JSON sent is not a valid Request object.
*/
const INVALID_REQUEST = -32600;

### 

/**
* Server error
* Method not found
* The method does not exist / is not available.
*/
const METHOD_NOT_FOUND = -32601;

### 

/**
* Server error
* Invalid params
* Invalid method parameter(s).
*/
const INVALID_PARAMS = -32602;

### 

/**
* Server error
* Internal JSON-RPC error.
*/
const JSON_RPC_ERROR = -32603;

### 

/**
* application error
*/
const APPLICATION_ERROR = -32500;

### 

/**
* system error
*/
const SYSTEM_ERROR = -32400;

### 

/**
* transport error
*/
const TRANSPORT_ERROR = -32300;

### 

/**
* Server error
* Reserved for implementation-defined server-errors.
* -32000 to -32099
*/


