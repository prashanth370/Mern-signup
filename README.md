# MERN Signup

A **MERN (MongoDB, Express, React, Node.js) Authentication System** with user signup, login, and authentication using JWT.

## 🚀 Features

- User registration with secure password hashing using `bcryptjs`
- User login with JWT-based authentication
- MongoDB as the database (using Mongoose)
- Express.js for the backend API
- React.js for the frontend UI
- Environment variables for security (`dotenv`)
- CORS enabled for frontend-backend communication

---

## 📂 Project Structure


---

## 🛠 Tech Stack

| Technology | Description |
|------------|------------|
| **MongoDB** | NoSQL database for storing user data |
| **Express.js** | Node.js framework for backend APIs |
| **React.js** | Frontend framework for user interface |
| **Node.js** | Backend runtime environment |
| **JWT (jsonwebtoken)** | Token-based authentication |
| **bcryptjs** | Password hashing for security |
| **Mongoose** | MongoDB ODM (Object-Document Mapping) |
| **Nodemon** | Auto-restart server in development |
| **dotenv** | Environment variable management |
| **CORS** | Middleware for frontend-backend communication |

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/prashanth370/Mern-signup.git
cd Mern-signup

cd backend
npm install
cd frontend
npm install
npm run dev
npm run dev  # Development mode (nodemon)
npm run start # Production mode
