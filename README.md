# Task Manager API

Simple RESTful API using Node.js, Express.js, and MongoDB for managing tasks.

## Features
- Create, Read, Update, Delete (CRUD)
- Input validation
- Error handling
- MongoDB via Mongoose
- Environment variable configuration

## Usage
1. Clone repository
2. Create `.env` file with `MONGO_URI` and `PORT`
3. Run `npm install`
4. Start with `npm run dev` (nodemon) or `npm start`

## API Endpoints
- `POST /api/tasks` – Create task
- `GET /api/tasks` – Get all tasks
- `GET /api/tasks/:id` – Get task by ID
- `PUT /api/tasks/:id` – Update task
- `DELETE /api/tasks/:id` – Delete task
