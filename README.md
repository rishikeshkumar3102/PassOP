# passOP

🔐 **passOP** is a password manager application designed to securely manage passwords.

## Project Overview

- **Retrieve Passwords**: Fetch all stored passwords from the database.
- **Save Passwords**: Save passwords securely by hashing them using bcrypt before storing them.
- **Delete Passwords**: Delete passwords from the database based on a given identifier.

## Tech Stack

- **Express.js**: 🚀 Web framework for handling HTTP requests and defining API endpoints.
- **MongoDB**: 🗄️ NoSQL database to store password data.
- **Middleware**:
  - **body-parser**: 📦 Parses incoming request bodies to handle JSON payloads.
  - **cors**: 🌐 Handles Cross-Origin Resource Sharing to allow requests from different origins.
- **bcryptjs**: 🔒 Provides password hashing and salting for secure storage.
- **MongoClient**: 🔗 Connects to MongoDB for database operations.
- **JavaScript**: 📜 Language used for server-side logic.

## Additional Notes

- **Port**: 🌐 The application listens on port 3000.
- **Endpoints**:
  - `GET /`: Retrieve all passwords.
  - `POST /`: Save a new password (with hashing).
  - `DELETE /`: Delete a password.
