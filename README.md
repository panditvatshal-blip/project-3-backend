# Project 3: Database Integration (Node.js + Express + MongoDB Atlas)

A RESTful API backend built with Node.js, Express, and Mongoose (MongoDB) that supports full CRUD operations (Create, Read, Update, Delete) on database models.

---

## 🛠️ Tech Stack & Prerequisites

- **Runtime Environment:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB Atlas (Cloud Database)
- **Object Data Modeling (ODM):** Mongoose
- **Environment Management:** Dotenv

---

## 📁 Project Structure

```text
backend/
├── controllers/
│   └── itemController.js   # Handles request logic for CRUD operations
├── models/
│   └── item.js             # Mongoose schema for Item resources
├── routes/
│   └── itemRoutes.js       # Express route handlers
├── .env                    # Environment configuration (Ignored by Git)
├── package.json            # Dependencies and scripts
└── server.js               # Express app entry point & DB connection
