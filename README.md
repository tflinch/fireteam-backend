# Project FireTeam ReadME.

Backend Web Server. Servering RESTful API using Node.JS and Express. MongoDB, Mongoose, JWT, bcrypt.js, dotenv, and Render for deployment.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (JSON Web Tokens)
- bcrypt.js
- dotenv

## Features

User Routes

- POST /users/signup: Register a new user.
- POST /users/signin: Sign in an existing user.
- GET /users: Get a list of all users.
- PUT /users/:id: Update user details.


## Models
User Model (models/user.js) Defines the schema for user data including:

- username: A unique identifier for the user.
- hashedPassword: The user's hashed password.
- role: The user's role, either 'user' or 'admin'.
- name: The user's full name.
- phoneNumber: The user's contact number.
- country: The user's country of residence.
- state: The user's state of residence.
- email: The user's email address.
