Here's your properly formatted README with images and headings:  

---

# Full-Stack WebSocket Chat System  

## 📌 Overview  
This project is a real-time chat application built using WebSockets. It enables multiple users to communicate in real-time with features like connection handling, message validation, private messaging, and chat history storage.  

## 🛠 Tech Stack  
- **Backend**: Node.js, Express.js, WebSocket.io, MongoDB  
- **Frontend**: React.js, Context API, WebSocket API, TailwindCSS  

## ✨ Features  
✅ Real-time messaging via WebSockets  
✅ Broadcast messages to all connected clients  
✅ User-friendly chat UI with message display  
✅ Connection handling (disconnect, reconnect)  
✅ Input validation to prevent empty messages  
✅ Private messaging (Bonus Feature)  
✅ Group chat support  
✅ Chat history stored in MongoDB (Bonus Feature)  

## 📁 Project Structure  
### 🔹 Backend (`chat-live-backend`)  
- `server.js` – WebSocket server with Express  
- `models/Message.js` – Mongoose schema for storing messages  
- `routes/chat.js` – API endpoints for retrieving chat history  

### 🔹 Frontend (`chat-live-frontend`)  
- `components/Chat.js` – Chat UI component  
- `context/ChatContext.js` – WebSocket connection management  
- `pages/index.js` – Main chat page  

## 🚀 Setup Instructions  
### 🖥 Backend  
1. Clone the repository:  
   ```bash
   git clone https://github.com/mathiyazhagan-d/chat-live-backend.git
   cd chat-live-backend
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Start the server:  
   ```bash
   node server.js
   ```  
4. The WebSocket server will run on `ws://localhost:5000`  

### 💻 Frontend  
1. Clone the repository:  
   ```bash
   git clone https://github.com/mathiyazhagan-d/chat-live-frontend.git
   cd chat-live-frontend
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Start the frontend:  
   ```bash
   npm run dev 
   ```  
4. Open `http://localhost:3000` in the browser  

## 🖼 Screenshots  

### 🔹 Login Page  
<img src="https://github.com/mathiyazhagan-d/chat-live-frontend/public/screenshot/img (1).png" alt="Login Page" width="600">  

### 🔹 Signup Page  
<img src="https://github.com/mathiyazhagan-d/chat-live-frontend/public/screenshot/img (2).png" alt="Signup Page" width="600">  

### 🔹 Search User  
<img src="https://github.com/mathiyazhagan-d/chat-live-frontend/public/screenshot/img (6).png" alt="Search User" width="600">  

### 🔹 User Profile  
<img src="https://github.com/mathiyazhagan-d/chat-live-frontend/public/screenshot/img (4).png" alt="Profile Page" width="600">  

### 🔹 Group and Direct Chat  
<img src="https://github.com/mathiyazhagan-d/chat-live-frontend/public/screenshot/img (3).png" alt="Group and Direct Chat" width="600">  

### 🔹 Group Details Edit  
<img src="https://github.com/mathiyazhagan-d/chat-live-frontend/public/screenshot/img (6).png" alt="Group Details Edit" width="600">  

## 📝 Additional Notes  
- Implemented **context API** to manage WebSocket connections globally.  
- Used **MongoDB** for chat history storage with a simple REST API.  
- Improved UI/UX with **TailwindCSS** for responsiveness.  
- Handled edge cases: empty messages, connection loss, auto-reconnect.  

## 👨‍💻 Author  
**Mathiyazhagan D**  

