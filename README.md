# FaunaVault 🦁🌿

**Your Encyclopedia of Animal Species**

This is a project made by me since I've always had an interest in animals and I'd like to put it in real life!

---

## 🌍 About the Project

**FaunaVault** is a full-stack web application designed to be a digital vault of animal species around the world. It allows users to explore, learn, and contribute information about diverse animal species. This project combines modern technologies to deliver an engaging and scalable platform for wildlife enthusiasts.

---

## 🚀 Tech Stack

### Frontend
- **React** - For building the user interface
- **Tailwind CSS** - For fast and responsive styling
- **Axios** - For making HTTP requests to the backend
- **React Router** - For routing and navigation

### Backend
- **Node.js + Express.js** - For building the API server
- **Prisma ORM** - For interacting with PostgreSQL database
- **dotenv** - For managing environment variables
- **CORS** - For handling cross-origin requests
- **bcrypt** - For secure password hashing
- **jsonwebtoken (JWT)** - For authentication

### Database
- **PostgreSQL**

### Api
-**https://api-ninjas.com/api/animals**

---

## 📄 Project Structure

```
faunavault/
├── backend/
│   ├── prisma/
│   ├── src/
│   ├── .env
│   └── package.json
├── frontend/
│   ├── public/
│   ├── src/
│   ├── tailwind.config.js
│   ├── .env
│   └── package.json
├── database/
│   └── schema.sql (Optional)
└── README.md
```

---

## 🔥 Installation & Setup

### Backend
```bash
cd backend
npm install
npx prisma init
# Add your PostgreSQL connection string in .env
npx prisma migrate dev --name init
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

---

## 🌱 Core Features

✅ Explore animal species database  
✅ View detailed information about each species  
✅ User authentication (optional for contributors)  
✅ Add new species (authenticated users)  
✅ Responsive and modern UI with Tailwind

---

## 🗂️ Next Goals

- Add filtering & search for species
- Improve UI/UX with animations & better layouts
- Add contributor system for logged-in users
- Create admin routes for content management

---
