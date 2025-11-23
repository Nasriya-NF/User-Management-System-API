**User Management System API**
* Overview
    * This is a RESTful API for User Management built with Node.js, Express, and MongoDB.
    * It supports user registration, login with JWT authentication, and CRUD operations for user data.
    * Passwords are securely hashed using bcrypt.
      
* Features
     * User Registration (POST /api/auth/register)
     * User Login (POST /api/auth/login)
     * JWT Authentication for protected routes
     * Create User (POST /api/users)
     * Read Users (GET /api/users)
     * Update User (PUT /api/users/:id)
     * Delete User (DELETE /api/users/:id)
     * Environment variables for secure configuration

* Technologies Used
    * Node.js
    * Express.js
    * MongoDB & Mongoose
    * JWT Authentication (jsonwebtoken)
    * Password hashing (bcryptjs)
    * Postman for testing
 
* Setup Instructions
     1. Clone the repository
        * git clone <your-repo-url>
        * cd user-management-api
         
     2. Install dependencies
        * npm install
        * MONGO_URI=<Your MongoDB Connection URL>
        * PORT=5000
        * JWT_SECRET=<YourSecretKey>

     3. Create a .env file
        * MONGO_URI=<Your MongoDB Connection URL>
        * PORT=5000
        * JWT_SECRET=<YourSecretKey>


     5. Run the server
        * npm start
        * Server will run on http://localhost:5000
