# 🛒 Simple E-Commerce API

A basic full-stack e-commerce application built using **Node.js**, **Express**, **MongoDB**, and a simple **HTML frontend**. It supports **product listing**, **cart management**, **order creation**, and **role-based authentication** using JSON Web Tokens (JWT).

## 🚀 Features

- 🔐 User registration and login with JWT authentication
- 👥 Role-based access control (Customer & Admin)
- 🛍️ Product listing with search and pagination
- 🛒 Cart: Add, update, remove items
- 📦 Order creation from cart
- 🖥️ Simple HTML + JS frontend to interact with the API

## 📁 Folder Structure


## 🛠️ Tech Stack

- Backend: Node.js, Express.js
- Database: MongoDB with Mongoose
- Auth: JWT + Bcrypt
- Frontend: HTML + Vanilla JS

## ⚙️ How to Run Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
MONGO_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your_jwt_secret
PORT=5000
