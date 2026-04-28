# Лабораторная работа №35. Подключаем фронтенд к API: доска мемов
**Выполнила:** Телятникова Е.П.

**Группа:** ИСП-231

## Как запустить проект
### 1. Запуск бэкенда
1. Откройте терминал и перейдите в папку с проектом API:
   ```bash
   cd MemesApi
   ```
2. Запустите сервер:
   ```bash
   dotnet run
   ```
3. Сервер запустится по адресу: `http://localhost:5000`
   - API мемов доступно по: `http://localhost:5000/api/memes`
   - Swagger документация: `http://localhost:5000/swagger`
### 2. Запуск фронтенда (HTML + CSS + JS)
1. Откройте папку `frontend` в VS Code.
2. Щёлкните правой кнопкой мыши по файлу `index.html`.
3. Выберите **"Open with Live Server"**.
4. Страница откроется по адресу типа `http://127.0.0.1:5500/index.html`
## Что изучили в ходе работы

| Концепция | Где используется |
|---|---|
| `fetch(url)` | GET-запрос к API |
| `fetch(url, { method, headers, body })` | POST и DELETE запросы |
| `response.ok` | Проверка успешности ответа |
| `response.json()` | Чтение JSON из ответа |
| `JSON.stringify(...)` | Объект JS → JSON-строка для отправки |
| `async / await` |Ожидание ответа от сервера |
| `try / catch / finally` | Обработка ошибок при fetch |
| `CORS (Cross-Origin Resource Sharing)` | Разрешение запросов между разными портами |
| `AddCors` + `UseCors` | Включение CORS в ASP.NET Core — два шага |
