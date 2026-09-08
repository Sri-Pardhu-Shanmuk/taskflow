# 📝 TaskFlow

A simple full-stack To-Do List application built to understand how a web application connects from the **Frontend → Backend → Database**.

---

## 🚀 Features

* ➕ Add new tasks
* 📝 View active tasks
* ✅ Complete tasks
* ↩️ Undo completed tasks
* 🗑️ Delete tasks
* 🕒 View completed task history
* 📅 Store completion date and time
* 💾 Store tasks using SQLite

---

## 🛠️ Technologies Used

| Technology | Purpose                                    |
| ---------- | ------------------------------------------ |
| HTML       | Creates the structure of the webpage       |
| CSS        | Styles the user interface                  |
| JavaScript | Handles user interactions and API requests |
| Python     | Handles backend logic                      |
| Flask      | Creates the backend API                    |
| SQLite     | Stores task data                           |
| Git        | Tracks project changes                     |
| GitHub     | Hosts the project repository               |

---

## 📂 Project Structure

```text
todo-project/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── backend/
│   └── app.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🔄 Application Flow

```text
User
  ↓
Frontend
HTML + CSS + JavaScript
  ↓
Flask Backend
Python
  ↓
SQLite Database
tasks.db
  ↓
Response
  ↓
Frontend
  ↓
User
```

---

## ▶️ Run Locally

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Go to the project folder

```bash
cd todo-project
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python backend/app.py
```

### 5. Open in your browser

```text
http://127.0.0.1:5000
```

---

## 🔍 Understanding the Project

### Add Task Flow

```text
User clicks Add Task
        ↓
script.js
        ↓
POST /tasks
        ↓
Flask Backend
        ↓
INSERT INTO tasks
        ↓
SQLite Database
        ↓
GET /tasks
        ↓
Task appears on screen
```

---

## 🎯 Learning Objectives

This project helps beginners understand:

* Frontend development
* Backend development
* API communication
* Database operations
* CRUD operations
* Git and GitHub
* Project deployment
* How to trace and understand an existing project

---

## 👨‍💻 Author

Created as a beginner-friendly Full-Stack Development project.
"# taskflow" 
