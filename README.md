# Task Manager API (MERN Backend)

## 📌 Project Overview

This is a Task Manager backend application built using Node.js, Express, and MongoDB.
It includes user authentication and task management features.

---

## 🚀 Features

* User Registration & Login (JWT Authentication)
* Password Hashing using bcrypt
* Protected Routes using Middleware
* Task CRUD API (Create, Read, Update, Delete)
* Environment Variables for security

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT (jsonwebtoken)
* bcryptjs

---

## ⚙️ Setup Instructions

1. Clone the repository
2. Navigate to backend folder

```
cd backend
```

3. Install dependencies

```
npm install
```

4. Create `.env` file in backend folder

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

5. Start the server

```
npm start
```

---

## 📂 Project Structure

```
backend
│
├── models
├── controllers
├── routes
├── middleware
├── config
├── server.js
└── .env
```

---

## 🔐 Security Note

* `.env` file is added to `.gitignore`
* Sensitive data like database URL and JWT secret are not exposed

---

## 🧠 Approach

* Used modular folder structure for clean code
* Separated concerns (routes, controllers, models)
* Implemented authentication using JWT
* Ensured secure password handling with bcrypt

---

## 📌 Current Status

✔ Project structure setup
✔ Authentication completed
✔ CRUD APIs in progress

---

## ✨ Future Improvements

* Pagination & Search
* Role-Based Access Control
* React Frontend Integration
* Deployment

---
