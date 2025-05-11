# ✨ Full Stack Realtime Chat App ✨

### Deployed App: 

    https://realtime-chat-app-z6sw.onrender.com/login

### 🧩 Overview  

A full-stack web application that enables real-time messaging between users, along with live user presence, customizable chat themes, and profile image updates.

### 🚀 Highlights:

- ⚙️ Tech Stack: MERN (MongoDB, Express, React, Node.js), Socket.io, TailwindCSS, DaisyUI
- 🔐 Auth: Secure Authentication & Authorization using JWT
- 💬 Real-Time Messaging: Built with Socket.io for fast, bi-directional communication
- 🟢 Online User Status: Instantly displays user presence
- 🌐 Global State Management: Managed with Zustand
- 🛡️ Robust Error Handling: On both client and server sides for better reliability
- 🎨 Theming & Profile: Users can update their profile picture and customize chat theme colors
- 🐞 Error Handling: Both on the server and on the client

### 🛠️ Challenges & Solutions  

**Challenge:** Enabling reliable, low-latency communication between users  
**Solution:** Implemented WebSockets (via Socket.IO) for real-time data flow  

**Challenge:** Ensuring robust error handling across a distributed architecture  
**Solution:** Built centralized error handling in both the client and Node.js backend 

### 📈 Outcomes

- Delivered a seamless chat experience with <100ms message delivery time  
- Designed a responsive and accessible UI for desktop and mobile users  
- Implemented secure and scalable architecture suitable for production use

### Setup .env file

```js
PORT=5001
MONGO_DB_URI=...
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
