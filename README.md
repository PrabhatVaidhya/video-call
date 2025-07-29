
# 🎥 Streamify – Real-Time Video Calling Platform

**Developed by Prabhat Vaidhya**

Streamify is a full-stack, research-backed web application designed to facilitate **real-time peer-to-peer video communication**. Built with modern technologies like WebRTC and Socket.io, Streamify enables seamless, secure, and scalable video calling—integrated with user authentication and social features such as friend requests and private chat.

---

## 🧠 Motivation

The demand for **real-time communication tools** has surged in the era of remote work, virtual collaboration, and digital socializing. Streamify aims to address this by building a full-stack system that replicates core functionality seen in tools like Zoom, Google Meet, and Microsoft Teams—using **open-source technologies** and **low-latency protocols**.

---

## 🚀 Key Features

- 🔐 **JWT-Based Secure Authentication**
- 📬 **Friend Request System** with connection management
- 📹 **WebRTC-Powered Real-Time Video Calling**
- 💬 **Socket.io-Based Instant Messaging**
- 🧑‍💼 **User Dashboard and Profile System**
- 📡 **Scalable WebSocket Integration**

---

## 🛠️ Tech Stack Overview

| Layer       | Tools Used                                      |
|-------------|--------------------------------------------------|
| Frontend    | React.js, TailwindCSS, WebRTC, Socket.io-client |
| Backend     | Node.js, Express.js, MongoDB, Socket.io         |
| Auth & DB   | JWT, bcrypt.js, MongoDB                         |
| Deployment  | Node.js server, potential for Docker/Cloud      |

---

## 🧱 Project Structure

```
streamify-video-calls/
├── backend/
│   ├── src/
│   │   ├── controllers/    # Handles business logic
│   │   ├── lib/            # Database & stream utilities
│   │   ├── middleware/     # JWT & auth checks
│   │   ├── models/         # MongoDB schemas
│   │   └── routes/         # RESTful APIs
├── frontend/
│   ├── public/
│   └── src/                # React components and context
```

---

## ⚙️ Getting Started

### 📦 Prerequisites

- Node.js v16+
- MongoDB (local or cloud)
- npm or yarn

### 🚀 Clone and Install

```bash
git clone https://github.com/prabhat-vaidhya/streamify-video-calls.git
cd streamify-video-calls
```

### 🔧 Backend Setup

```bash
cd backend
cp .env.example .env
npm install
npm run dev
```

> The backend server runs on **http://localhost:5000**

### 🎨 Frontend Setup

```bash
cd ../frontend
cp .env.example .env
npm install
npm start
```

> The React app runs on **http://localhost:3000**

---

## 🔐 Environment Variables

### Backend `.env`

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/streamify
JWT_SECRET=your_secure_jwt_secret
```

### Frontend `.env`

```env
REACT_APP_API_URL=http://localhost:5000
```

---

## 📜 Core Scripts

| Location   | Script          | Function                       |
|------------|------------------|--------------------------------|
| `backend`  | `npm run dev`    | Start backend using Nodemon   |
| `frontend` | `npm start`      | Start frontend React app       |
| `frontend` | `npm run build`  | Build optimized React app     |

---

## 📊 Research & Implementation Notes

- **WebRTC (Web Real-Time Communication)** is used for peer-to-peer video and audio streams, minimizing latency and server load.
- **Socket.io** provides bidirectional, event-based communication for signaling and chat features.
- **MongoDB** is used to manage user data, friend requests, and authentication securely and flexibly.
- The project structure follows **MVC design pattern**, ensuring code modularity and scalability.

---

## 🤝 Contribution Guidelines

Pull requests are welcome! If you have ideas for improvements or new features, feel free to fork the repo and submit a PR.  
To discuss major changes, open an issue first.

---


## 👨‍💻 Author

**Prabhat Vaidhya**  

---

> *Streamify is built as a portfolio-grade project to demonstrate real-time systems, secure API design, and frontend-backend integration in modern web development.*
