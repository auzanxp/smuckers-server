## install

```bash
1. npm install
2. npm install -g sequelize sequelize-cli
3. sequelize db:create
4. sequelize db:migrate
5. sequelize db:seed:all
```

# ROUTE BOOK

> GET | `/books`

- fetch all data
  > GET | `/books/{id}`
- fetch data detail
- > POST | `/login`
- login first to get access_token
  > POST | `books/create`
- add a new data, you must send a token (login first)
Payload: \
  title: \
  author: \
  publisher: \
  year: (integer) \
  isbn: \
  language: \
  page: \
  length: \
  weigth: \
  width: \
  cover: (URL IMAGE) \
  description: \
  category: \
  rating:
  > PUT | `books/:id/edit`
- edit data (MANDATORY SEND ID)
Can submit one of payload below: \
  title: \
  author: \
  publisher: \
  year: (integer) \
  isbn: \
  language: \
  page: \
  length: \
  weigth: \
  width: \
  cover: (URL IMAGE) \
  description: \
  category: \
  rating:
  > DELETE | `books/:id`
- delete data (MANDATORY SEND ID) \
