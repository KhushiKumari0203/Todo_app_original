# 📝 Todo App

A full-stack Todo application with user authentication, task management, and persistent data storage.

![to do app login](https://github.com/user-attachments/assets/bd24143a-8b4c-47dc-a17e-903a34862fbe)
1. LOGIN PAGE 


![WhatsApp Image 2025-06-11 at 6 42 21 PM](https://github.com/user-attachments/assets/bdc021af-c502-4b16-bafe-32ce6579527b)
2. Task Page




---

## 🚀 Features

- 🔐 User Login & Signup
- ✅ Add, Edit, Delete, and View Tasks
- 📦 Full-stack: React (frontend) + Express + MongoDB (backend)
- 🌐 Frontend deployed on Netlify
- 🖥️ Backend deployed on Render

---

## 📁 Folder Structure

todo_app/

├── backend/ # Node.js + Express + MongoDB backend

│ ├── controllers/ # Route handler logic (e.g., auth, task)

│ ├── models/ # Mongoose models (User, Task)

│ ├── routes/ # Express routes

│ ├── middleware/ # Middleware (auth checks, etc.)

│ ├── .env # Environment variables

│ ├── app.ts # Express app setup

│ └── server.ts # Entry point for the backend

│
├── frontend/ # React + TypeScript frontend

│ ├── src/

│ │ ├── components/ # Reusable UI components

│ │ ├── pages/ # Page-level components (Home, Login, AddTask)

│ │ ├── App.tsx # Main app component

│ │ ├── index.tsx # React DOM render

│ │ └── services/ # API calls (e.g., auth, tasks)

│ └── vite.config.ts # Build configuration (if using Vite)

│
├── .gitignore

├── README.md

└── package.json # Root-level config 



---

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/KhushiKumari0203/Todo_app_original.git
cd Todo_app_original
```

Install dependencies
bash
Copy
Edit
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install


## Run the development servers
bash
Copy
Edit
# In backend/
npm run dev

# In frontend/
npm run dev
🌍 Deployment
Frontend: Netlify

# Backend: Render +uptimeRobot

📌 License
This project is licensed under the MIT License.

🙋‍♀️ Author
Khushi Kumari
