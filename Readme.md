# 📦 Backend API - Jokes Service

## 🚀 Overview

This is a simple backend built using **Node.js** and **Express.js** that provides a list of jokes via an API.

---

## 🛠️ Tech Stack

- Node.js
- Express.js

---

## 📂 Project Structure

```
server/
│
├── index.js        # Main server file
├── package.json
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/BariyaVasu/backend-project.git
```

2. Navigate to project

```bash
cd server
```

3. Install dependencies

```bash
npm install
```

---

## ▶️ Run Server

```bash
npm start
```

or (if using nodemon)

```bash
npm run dev
```

---

## 🌐 API Endpoints

### 🔹 Get All Jokes

```
GET /api/jokes
```

### ✅ Response Example

```json
[
  "Why did the chicken cross the road? To get to the other side!",
  "Why did the scarecrow win an award? Because he was outstanding in his field!",
  "Why don't scientists trust atoms? Because they make up everything!"
]
```

---

## 🔌 Server Configuration

Default Port:

```
http://localhost:3000
```

You can change the port using environment variables.

---

## ❗ Error Handling

- Basic error handling is implemented
- Returns JSON response

---

## 📌 Notes

- This is a simple demo API
- No database is used
- Data is hardcoded

---

## 🚀 Future Improvements

- Add MongoDB database
- Add CRUD operations (Create, Update, Delete)
- Add authentication
- Add validation

---

## 👨‍💻 Author

Bariya Vasu
