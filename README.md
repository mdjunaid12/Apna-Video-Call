# Apna-Video-Call 🎥

A full-stack, real-time video conferencing web application clone. Experience seamless video and audio communication with a modern, responsive interface.

🌐 **Live Demo:** [https://apna-video-call-frontend-da5v.onrender.com](https://apna-video-call-frontend-da5v.onrender.com)

## 🚀 Features

- **Real-time Video & Audio Calls** - Peer-to-peer communication
- **Live Chat** - Message participants during meetings
- **Modern UI/UX** - Clean Material-UI interface
- **Room Management** - Create/join meeting rooms
- **User Authentication** - Secure login/registration

## 🛠️ Tech Stack

**Frontend:** React, Material-UI, React Router, Axios, Socket.io Client  
**Backend:** Node.js, Express.js, Socket.io, Mongoose, Bcrypt  
**Database:** MongoDB Atlas  
**Deployment:** Render

## 🎯 Quick Start

1. Visit: [https://apna-video-call-frontend-da5v.onrender.com](https://apna-video-call-frontend-da5v.onrender.com)
2. Sign up or log in
3. Create a new meeting or join with a room ID
4. Allow camera/microphone permissions
5. Start video calling!

## 📦 Local Development

### Prerequisites
- Node.js (v18+)
- MongoDB instance

### Frontend Setup
cd frontend
npm install
echo "REACT_APP_API_BASE_URL=http://localhost:5000" > .env
npm start

### Backend Setup
cd backend
npm install
echo "PORT=5000" > .env
echo "MONGODB_URI=your_mongodb_connection_string" >> .env
echo "JWT_SECRET=your_jwt_secret" >> .env
npm run dev

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
