# 🪶 Chirp Knot

A modern social media app that connects people through real-time updates, conversations, and threads.  
Built with **Expo + React Native** for mobile and **Express + MongoDB** for backend.

---

## 🚀 Features

- 📱 **Mobile-first** social experience with Expo + React Native
- 🔐 **Authentication** powered by Clerk
- 💬 **Posts & Threads** with media upload (images, etc.)
- ☁️ **Cloudinary** integration for image hosting
- 🛡️ **Secure APIs** with Express & Clerk middleware
- 📡 **Real-time ready** backend architecture with Express + MongoDB
- 🎨 **Tailwind (NativeWind)** for consistent styling

---

## 🛠️ Tech Stack

### Frontend (Mobile)

- Expo (React Native)
- React 19
- Expo Router
- NativeWind (Tailwind for RN)
- Clerk Expo SDK (Auth)
- TanStack React Query
- Axios
- Date-fns

### Backend (API)

- Node.js (ESM)
- Express 5
- MongoDB + Mongoose
- Clerk Express (Auth)
- Cloudinary (media storage)
- Multer (file upload)
- CORS + dotenv

---

## ⚙️ Setup & Installation

### 1. Clone the repo

```bash
git clone https://github.com/your-username/chirp-knot.git
cd chirp-knot

2. Install dependencies
```

# Frontend

```
cd mobile
npm install

# Backend
```

cd backend
npm install

# ▶️ Running the App

```
Frontend (Mobile / Expo)

cd mobile
npm run start   # Start dev server
npm run android # Run on Android
npm run ios     # Run on iOS
npm run web     # Run on Web
```

```
Backend (API)

cd backend
npm run dev   # Dev mode with file watcher
npm start     # Production
```
