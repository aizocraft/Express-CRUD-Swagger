# Express-CRUD-Swagger
Express API with Swagger Documentation
🚀 Overview

This is a User Management API built with Node.js, Express, and MongoDB. It supports CRUD operations with proper API documentation using Swagger.
📌 Features

    📄 Swagger Documentation (/api-docs)
    🔐 User Authentication (if applicable)
    📡 RESTful API with GET, POST, PUT, DELETE
    💾 MongoDB Integration with Mongoose
    🛠️ Environment Variables support with .env

🛠️ Installation & Setup
1️⃣ Clone the Repository

git clone https://github.com/aizocraft/Express-CRUD-Swagger.git
cd express-api

2️⃣ Install Dependencies

npm install

3️⃣ Setup Environment Variables

Create a .env file in the root directory and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string

4️⃣ Start the Server

For normal mode:

npm start

🔗 API Documentation

After running the server, visit:
📄 Swagger UI: http://localhost:5000/api-docs
📂 Folder Structure

/express-api
│-- /models        # Mongoose Schemas  
│-- /routes        # API Routes  
│-- server.js      # Main server file  
│-- .env           # Environment variables  
│-- package.json   # Dependencies  
│-- README.md      # Project documentation  

📜 API Endpoints
Method	Endpoint	Description
POST	/users	Create a new user
GET	/users	Get all users
PUT	/users/:id	Update a user
DELETE	/users/:id	Delete a user
