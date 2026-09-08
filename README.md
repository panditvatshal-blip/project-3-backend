Project 3: Database Integration (Node.js + Express + MongoDB Atlas)
A RESTful API backend built with Node.js, Express, and Mongoose (MongoDB) that supports full CRUD operations (Create, Read, Update, Delete) on database models.

Tech Stack & Prerequisites
Runtime Environment: Node.js

Framework: Express.js

Database: MongoDB Atlas (Cloud Database)

Object Data Modeling (ODM): Mongoose

Environment Management: Dotenv

Project Structure
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

API Endpoints Summary
POST /api/items - Create a new item

GET /api/items - Fetch all items

PUT /api/items/:id - Update an item by ID

DELETE /api/items/:id - Delete an item by ID

Environment Configuration
Create a .env file in the backend/ root directory with the following variables:

PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string

Local Setup & Execution
Clone the repository:
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

Navigate to the backend directory:
cd backend

Install dependencies:
npm install

Start the server:
node server.js
