# 🎓 Student CGPA API

A simple REST API built using **Node.js + Express.js** that manages student academic records using an **in-memory JSON array** (No database required).

---

## 📌 Project Objective

The goal of this assignment is to:

* Build RESTful APIs using Express.js
* Understand static and dynamic routing
* Perform filtering and aggregation using loops
* Return proper HTTP status codes
* Use middleware (`express.json`, `cors`)
* Work without a database (store data in memory)

---

## 🛠️ Technologies Used

* Node.js
* Express.js
* CORS Middleware
* JavaScript (Basic `for` loop logic)

---

## 📁 Folder Structure

```
Assignment-1/
│
├── node_modules/
├── .gitignore
├── index.js
├── package.json
└── package-lock.json
```

## ▶️ How to Run the Project Locally

### Step 1: Clone Repository

git clone https://github.com/mann2007-ptl/node-assignment1-CRUD

### Step 2: Navigate to Folder

cd Assignment-1

### Step 3: Install Dependencies

npm install

### Step 4: Start Server

node index.js

---

## 🌐 Server URL

http://localhost:3000

---

## 📊 Student Data Example

Each student record contains:

{
id: 1,
name: "Aarav Sharma",
branch: "CSE",
semester: 8,
cgpa: 9.3
}

---

## 🚀 API Routes Implemented

| Method | Route                        | Description                   |
| ------ | ---------------------------- | ----------------------------- |
| GET    | /students                    | Get all students              |
| GET    | /students/topper             | Get student with highest CGPA |
| GET    | /students/average            | Get average CGPA              |
| GET    | /students/count              | Get total number of students  |
| GET    | /students/:id                | Get student by ID             |
| GET    | /students/branch/:branchName | Get students by branch        |

---

## 📡 Middleware Used

* `express.json()` → Parses JSON requests
* `cors()` → Allows cross-origin access

---

## 📘 Learning Outcomes

* Understanding REST API structure
* Working with route parameters
* Performing server-side calculations
* Using loops to process data
* Handling HTTP responses correctly
* Preparing backend APIs for deployment

---

## 🌍 Deployment Link (Render)

Add your deployed link here:

https://node-assignment1-crud.onrender.com/

---

## 📬 Postman Documentation

Add your Postman documentation link here:

https://documenter.getpostman.com/view/50840766/2sBXcEmgCf

---

## 👨‍💻 Author

Mann Patel
