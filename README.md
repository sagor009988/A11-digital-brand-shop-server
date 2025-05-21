# 🛍️ Digital Brand Shop

**Digital Brand Shop** is a responsive, user-friendly e-commerce web application that allows users to browse and search for digital products by category, view product details, and interact with a sleek modern UI. Built using the MERN stack with Firebase for authentication.

## 🚀 Features

- 🔍 **Category-Based Search**: Easily filter products by category to find what you need.
- 🛒 **Product Details View**: Click on any product to see full details including description, price, and specifications.
- 📱 **Responsive Design**: Optimized for all devices — mobile, tablet, and desktop.
- 👥 **User-Friendly UI**: Smooth navigation with a clean and intuitive interface.

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Authentication**: Firebase Auth
- **Database**: MongoDB

## 📂 Project Structure

client/ # React frontend
├── components/ # Reusable UI components
├── pages/ # Main page views (Home, Products, etc.)
└── App.js

server/ # Node.js + Express backend
├── models/ # MongoDB models
├── routes/ # API routes
└── server.js

bash
Copy
Edit

## 🔧 Installation

### Prerequisites

- Node.js and npm
- MongoDB
- Firebase project

### Clone the Repo

```bash
git clone https://github.com/your-username/digital-brand-shop.git
cd digital-brand-shop
Backend Setup
bash
Copy
Edit
cd server
npm install
# Create a `.env` file and add your MongoDB URI and Firebase config
npm run dev
Frontend Setup
bash
Copy
Edit
cd client
npm install
npm start
