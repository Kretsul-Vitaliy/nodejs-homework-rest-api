### Тестовий проект домашней работы:

Работа по REST API, с контактами в базе данных MongoDB ( db-contacts коллекция contacts).

### Пример контакта:

- {
  - "name": "Ahkiollk test",
  - "email": "nulluia.ante@vestibul.co",
  - "phone": "(292) 974-8880",
  - "favorite": false
  - }

### REST API

1. (метод get) список всех контактов

- /api/v1/contacts/

2. (метод get) информация о контакте по ID

- /api/v1/contacts/:contactId

3. (метод post) добавление нового контакта с полями {name, email, phone}

- /api/v1/contacts/:contactId

4. (метод delete) удаление контакта по ID

- /api/v1/contacts/:contactId

5. (метод put) изменение контакта по ID (с переданными полями {name, email, phone})

- /api/v1/contacts/:contactId

6. (метод patch) изменение статуса контакта по ID (с переданным boolean полем {favorite})

- /api/v1/contacts/:contactId/favorite

### Команды:

- `npm start` &mdash; старт сервера в режиме production
- `npm run start:dev` &mdash; старт сервера в режиме разработки (development)
- `npm run lint` &mdash; запустить выполнение проверки кода с eslint, необходимо выполнять перед каждым PR и исправлять все ошибки линтера
- `npm lint:fix` &mdash; та же проверка линтера, но с автоматическими исправлениями простых ошибок
