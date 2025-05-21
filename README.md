# 🖥️ Digital Brand Shop – Server Side

This is the backend of the **Digital Brand Shop**, an e-commerce application that provides a category-based product search and detail viewing experience. The backend is built using **Node.js**, **Express.js**, and **MongoDB** with **Firebase Authentication** for secure access.

## 🚀 Features

- 🔐 Firebase-based authentication middleware
- 🗂️ Category-based product filtering
- 📦 Product CRUD operations
- 🌐 RESTful API endpoints
- 📡 Connected to MongoDB (Cloud or Local)

## 🛠️ Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (with Mongoose)
- **Auth**: Firebase Admin SDK
- **Middleware**: CORS, JSON Parser, Error Handler

## 📁 Project Structure

server/
├── controllers/ # Logic for handling API requests
├── models/ # Mongoose models
├── routes/ # Express route handlers
├── middleware/ # Custom middleware (auth, error handling)
├── utils/ # Utility functions
├── server.js # Main entry point
└── .env # Environment variables

bash
Copy
Edit

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/digital-brand-shop.git
cd digital-brand-shop/server
2. Install dependencies
bash
Copy
Edit
npm install
3. Create .env file
Create a .env file in the root of the server directory and add:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_uri
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_CLIENT_EMAIL=your_firebase_client_email
FIREBASE_PRIVATE_KEY=your_firebase_private_key (replace \n with real newlines)
