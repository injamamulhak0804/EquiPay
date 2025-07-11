# EquiPay 💸

**EquiPay** is a modern web application that helps users split expenses fairly among groups — perfect for roommates, trips, or team events.

---

## 🛠️ Tech Stack

### 📦 Frontend (Client)
- **Next.js** – React-based framework for SSR and static pages
- **TypeScript** – Strong typing for safer, maintainable code
- **Tailwind CSS** – Utility-first CSS for rapid UI development
- **ShadCN UI** – Pre-built, beautiful UI components
- **Axios** – For communicating with the backend API

### 🚀 Backend (Server)
- **Express.js** – Fast, minimalist Node.js server
- **CORS** – Handles cross-origin requests from Next.js frontend
- **dotenv** – Manages environment variables
- **Zod** – For request body validation (optional)
- **MongoDB** – Database to store users, groups, and expenses
- **Mongoose** – ORM/ODM for database interaction
- **Winston** - For logging the user logs. 

### 🔐 Authentication (Optional)
- **JWT (JSON Web Tokens)** – Secure user sessions
- **bcrypt** – For password hashing

### 🧪 Testing (Optional)
- **Jest** – For unit testing backend logic
- **React Testing Library** – For frontend component testing

---

## 📁 Project Structure

```
equipay-backend/
├── src/
│   ├── config/           # MongoDB connection, environment setup
│   │   └── db.ts
│
│   ├── controllers/      # Logic for each route (business logic)
│   │   └── user.controller.ts
│   │   └── expense.controller.ts
│
│   ├── models/           # Mongoose schemas/models
│   │   └── user.model.ts
│   │   └── expense.model.ts
│
│   ├── routes/           # API route definitions
│   │   └── user.routes.ts
│   │   └── expense.routes.ts
│
│   ├── middlewares/      # Middleware (auth, error handler, logger, etc.)
│   │   └── auth.middleware.ts
│   │   └── error.middleware.ts
│
│   ├── utils/            # Utility functions (JWT, validators, etc.)
│   │   └── generateToken.ts
│   │   └── logger.ts
│
│   ├── types/            # Custom TypeScript types/interfaces
│   │   └── user.interface.ts
│
│   ├── app.ts            # Express app config (middlewares, routes)
│   └── server.ts         # Starts the server
│
├── .env                  # Environment variables
├── .gitignore
├── package.json
├── tsconfig.json
├── README.md

```






---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/injamamulhak0804/equipay.git
```