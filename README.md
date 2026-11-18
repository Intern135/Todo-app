# Todo Management System

## 1. Project Overview

A full-stack Todo Management System that allows users to register, log in, and manage their personal tasks.

The application uses a Node.js and Express.js backend with an SQLite database.

## 2. Technologies Used

| Technology | Purpose |
|---|---|
| Node.js | Backend runtime |
| Express.js | Backend framework |
| SQLite | Database |
| HTML | Frontend structure |
| CSS | Frontend styling |
| JavaScript | Frontend functionality |
| bcrypt | Password hashing |
| JWT | User authentication |

## 3. Features

- User registration
- User login
- Password hashing
- JWT-based authentication
- Create todos
- Read todos
- Update todos
- Delete todos
- Frontend and backend integration

## 4. Project Structure

```text
chapter2/
├── public/
│   ├── index.html
│   ├── style.css
│   └── fanta.css
│
├── src/
│   ├── middleware/
│   ├── routes/
│   ├── db.js
│   └── server.js
│
├── .env
├── package.json
└── README.md
```

## 5. Installation

Clone the repository and install dependencies:

```bash
npm install
```

## 6. Environment Variables

Create a `.env` file in the project root.

Add the required environment variables:

```env
PORT=3000
JWT_SECRET=your_secret_key
```

Replace the example values with your actual configuration.

Never commit your real `.env` file to GitHub.

## 7. Running the Project

Start the development server:

```bash
npm run dev
```

## 8. Documentation

Additional technical documentation:

- API documentation: `docs/API.md`
- Database documentation: `docs/DATABASE.md`
- Architecture documentation: `docs/ARCHITECTURE.md`
