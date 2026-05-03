# 📌 Description
This is a fullstack Todo List application built with:
- React (Vite)
- Node.js + Express
- MongoDB

Users can add, mark as completed, and delete tasks.

# 🚀 Features
- Add new todo
- Mark todo as completed
- Delete todo
- Fetch todos from database

# 🛠️ Tech Stack
- Frontend: React (Vite)
- Backend: Node.js, Express
- Database: MongoDB
- HTTP Client: Axios

# ⚙️ How to Run
## 1. Run Backend
cd Server
npm install
node index.js

## 2. Run Frontend
cd todolist
npm install
npm run dev

# 🌐 API Endpoints
GET /get → get all todos
POST /add → add new todo
PUT /update/:id → mark as done
DELETE /delete/:id → delete todo
