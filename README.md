## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.



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
- **TypeScript** – Ensures consistency and type safety across the backend
- **CORS** – Handles cross-origin requests from Next.js frontend
- **dotenv** – Manages environment variables
- **Joi / Zod** – For request body validation (optional)
- **MongoDB or PostgreSQL** – Database to store users, groups, and expenses
- **Prisma / Mongoose** – ORM/ODM for database interaction

### 🔐 Authentication (Optional)
- **JWT (JSON Web Tokens)** – Secure user sessions
- **bcrypt** – For password hashing

### 🧪 Testing (Optional)
- **Jest** – For unit testing backend logic
- **React Testing Library** – For frontend component testing

---

## 📁 Project Structure