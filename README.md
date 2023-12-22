# TodoApi
A controller-based web API that uses a database, for creating, editing, retrieving and deleting to-do items.

## Specification

| API | Description | Request Body | Response Body |
|---|---|---|---|
| GET /api/todoitems | Get all to-do items | None | Array of to-do items |
| GET /api/todoitems/{id} | Get an item by ID | None | To-do item |
| POST /api/todoitems | Add a new item | To-do item | To-do item |
| PUT /api/todoitems/{id} | Update an existing item | To-do item | None |
| DELETE /api/todoitems/{id} | Delete an item | None | None |