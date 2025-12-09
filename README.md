# university_project_aubergine_Solutions
A simple Node.js + Express + MongoDB RESTful API for managing university students. This project is designed for learning and development purposes and includes Nodemon for automatic server restarts during development.

**Features**

CRUD operations for student data
MongoDB integration using Mongose
Express.js server
CORS enabled for cross-origin requests
Environment variables managed via .env
Automatic server restart with Nodemon
Modular project structure with routes

**Project Structure**
university-project/
│
├── index.js               # Main server file
├── package.json           # Project metadata & scripts
├── .env                   # Environment variables
├── nodemon.json           # Optional Nodemon config
└── routes/
    └── studentRoutes.js   # API routes for student CRUD operations
