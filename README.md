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

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/passOP.git
    ```
2. Navigate into the project directory:
    ```bash
    cd passOP
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Create a `.env` file in the root directory with the following content:
    ```
    MONGO_URI=your_mongodb_connection_string
    DB_NAME=your_database_name
    ```
5. Start the application:
    ```bash
    npm start
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
