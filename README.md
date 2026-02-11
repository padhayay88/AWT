# Todo App Backend

## Setup Instructions

1. Ensure MongoDB is running locally on port 27017.
2. Install dependencies:
   ```bash
   cd backend
   npm install
   ```
3. Start the backend server:
   ```bash
   npm start
   ```

## API Endpoints

- `GET /todos` — List all todos
- `POST /todos` — Create a new todo
- `PUT /todos/:id` — Update a todo
- `DELETE /todos/:id` — Delete a todo

## MongoDB
- Database: `todo-app`
- Collection: `todos`

## Requirements
- Node.js
- MongoDB

---

This backend uses Express and Mongoose for MongoDB integration.
