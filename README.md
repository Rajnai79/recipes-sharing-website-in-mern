# recipes-sharing-website-in-mern
A recipe-sharing platform built with the MERN stack (MongoDB, Express, React, Node.js). This web app allows users to share, discover, and save recipes, with features like user authentication, recipe creation, and search functionality.


---

## ⚙️ How to Run Locally

### 🔧 1. Backend Setup

```bash
cd backend
npm install
```
Create a .env file in the backend/ directory:
```
PORT=5000
MONGO_URI=mongodb://localhost:27017/recipesdb
JWT_SECRET=your_jwt_secret
```
Start the backend server:
```
npm start
```
💻 2. Frontend Setup
```
cd frontend
npm install
npm start
```
The frontend will run on:
👉 http://localhost:3000

🚀 Features
🍲 Browse and search for recipes,
📝 Detailed ingredients and cooking steps
🔐 User authentication (if enabled)
📱 Responsive design

