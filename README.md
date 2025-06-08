# 📚 Vinabook Clone – Fullstack Bookstore Website

This is a fullstack clone of [Vinabook.com](https://www.vinabook.com/) – a popular Vietnamese online bookstore.  
The project is built with **Next.js** for the frontend, **Node.js with Express** for the backend, **PostgreSQL** as the database, and **Zustand** for state management.

> 🚧 This project is under development and intended for learning and portfolio purposes only.

---

## ⚙️ Tech Stack

### 🖥️ Frontend
- [Next.js](https://nextjs.org/) – React framework with routing, SSR
- [TailwindCSS](https://tailwindcss.com/) – Utility-first CSS framework
- [Zustand](https://zustand-demo.pmnd.rs/) – Lightweight state management
- [Axios](https://axios-http.com/) – HTTP client

### ⚙️ Backend
- [Node.js](https://nodejs.org/) + [Express](https://expressjs.com/) – RESTful API
- [PostgreSQL](https://www.postgresql.org/) – Relational database
- [JWT](https://jwt.io/) – Authentication
- (Optional) [Prisma ORM](https://www.prisma.io/) – Type-safe database client

---

## 🚀 Features (Planned)

- 🔍 Search and filter books
- 📚 Browse by category and view book details
- 🛒 Add to cart (handled via Zustand)
- 👤 User authentication (JWT-based)
- 💳 Checkout flow (basic)
- 📦 Order management for users (optional)
- 🛠️ Admin dashboard (optional)
- 📱 Fully responsive UI

---

## 🧰 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/vinabook-clone.git
cd vinabook-clone
```

### 2. Environment Variables

Create a `.env` file in the `server/` folder:

```env
PORT=5000
DATABASE_URL=postgresql://your_user:your_password@localhost:5432/vinabook
JWT_SECRET=your_jwt_secret
```

If using Prisma, also run:

```bash
npx prisma init
```

---

### 3. Install dependencies

```bash
# Frontend
cd client
npm install

# Backend
cd ../server
npm install
```

---

### 4. Run development servers

```bash
# Start backend
cd server
npm run dev

# Start frontend
cd ../client
npm run dev
```

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use it for learning, remix it, and share with attribution.

---

## 📌 Disclaimer

This project is an **educational clone** of Vinabook.com and is not intended for commercial use.  
All content and functionality are recreated for portfolio and technical demonstration only.