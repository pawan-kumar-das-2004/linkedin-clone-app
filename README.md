# 🔗 LinkedIn Clone

A fully responsive and functional LinkedIn-like platform built with the MERN stack. Users can sign up, create posts, like/comment, follow others, and even post jobs!

---

## 👨‍💻 Author

**Pawan Kumar Das**

---

## 🌐 Live Demo

- 🔸 Frontend: [View Live](https://linkedin-clone-frontend.vercel.app)
- 🔹 Backend API: [View API](https://linkedin-clone-api.onrender.com)

---

## 🚀 Tech Stack

- **Frontend**: React (Vite) + Tailwind CSS
- **Backend**: Node.js + Express
- **Database**: MongoDB Atlas
- **Auth**: JWT (JSON Web Token)
- **Media Storage**: Cloudinary
- **Hosting**: Vercel (Frontend), Render (Backend)

---


## 🛠️ Setup Instructions (Local Development)

### 1. Clone the Repository

```bash
git clone https://github.com/pawan-kumar-das-2004/linkedin-clone-app.git
cd linkedin-clone-app
```

### 2. Install Dependencies

#### 📦 Backend
```bash
cd server
npm install
```

#### 📦 Frontend
```bash
cd client
npm install
```

### 3. Create `.env` Files

#### 🔐 For Backend (`server/.env`)
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

#### (Optional) For Frontend (`client/.env`)
```env
VITE_API_URL=http://localhost:5000/api
```


### 4. Run the App

#### ▶️ Start Backend
```bash
cd server
npm run dev
```

#### ▶️ Start Frontend
```bash
cd client
npm run dev
```

## Now open [http://localhost:5173](http://localhost:5173) in your browser to use the app.
---
