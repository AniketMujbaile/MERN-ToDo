# Todo App

This is a Todo App built with React.js for the frontend, Node.js and Express for the backend, and PostgreSQL for the database.

### 🔗 Hosted link

Hosted Link: [ToDo App](https://mern-to-do-seven.vercel.app/login)

## Features

- User authentication with JWT token
- CRUD operations for categories
- CRUD operations for todos
- CRUD operations for subtodos associated with each todo
- Search functionality for todos
- Pagination support for todos
- Filtering todos by category

## Technologies Used

- React.js
- TailwindCSS
- Express.js
- Postgres SQL
- JSON Web Tokens (JWT)
- bcrypt for password hashing

## Project Structure

The project is organized into two main folders: `client` and `server`.

### Client

The `client` folder contains the React.js application built with Tailwind for styling.

#### Installation

```bash
cd client
npm install
```

#### Usage

```bash
npm start
```

### Server

The `server` folder contains the Node.js and Express backend, along with the PostgreSQL database.


## Configuration File
1. Create a PostgreSQL database and update the connection details in `server/.env`.

```ENV

PORT=5000

DATABASE_URL=YOUR_URL

SECRET=YOUR_KEY
 
```
#### Installation

1. Install dependencies:

```bash
cd server
npm install
```

2. Run the server:

```bash
npm start
```

## Endpoints

- `POST /register`: Register a new user
- `POST /login`: Login and obtain a JWT token
- `GET /categories`: Get all categories
- `POST /addCategory`: Add a new category
- `DELETE /deleteCategory/:id`: Delete a category by ID
- `GET /todos`: Get all todos with optional pagination, search, and category filter
- `POST /addTodo`: Add a new todo
- `DELETE /deleteTodo/:id`: Delete a todo by ID
- `PUT /toggleTodo/:id`: Toggle the completion status of a todo
- `GET /subtodos/:todoId`: Get all subtodos for a specific todo
- `POST /addSubTodo`: Add a new subtodo to a specific todo
- `DELETE /deleteSubTodo/:id`: Delete a subtodo by ID
- `PUT /toggleSubTodo/:id`: Toggle the completion status of a subtodo

## Screenshots
<img src="https://github.com/AniketMujbaile/MERN-ToDo/blob/main/Img/Img1.png" width="500px">
<hr/>
<img src="https://github.com/AniketMujbaile/MERN-ToDo/blob/main/Img/Img2.png" width="500px">
<hr/>
<img src="https://github.com/AniketMujbaile/MERN-ToDo/blob/main/Img/Img3.png" width="500px">
<hr/>

 


