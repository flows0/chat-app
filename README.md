# 💬 Real-time Chat App
A full-stack real-time messaging application built with the MERN stack (MongoDB, Express, React, Node.js) and powered by Socket.IO for instant communication. Users can securely chat one-on-one, send images, and access messages instantly with full authentication and authorization flow.

## 📸 Screenshots
<img src="https://i.imgur.com/Cl2dwWB.png" alt="photo 1" />
<img src="https://i.imgur.com/CXKpaLY.png" alt="photo 2" />
<img src="https://i.imgur.com/3z6OnpN.png" alt="photo 3" />
<img src="https://i.imgur.com/R4ZtxTK.png" alt="photo 4" />
<img src="https://i.imgur.com/E0OmZLG.png" alt="photo 5" />

## 🛠️ Tech Stack
- **Frontend:** React, Tailwind CSS, daisyUI
- **Backend:** Node.js, Express
- **Database:** MongoDB (Mongoose)
- **Real-Time Engine:** Socket.IO
- **Authentication:** bcrypt, JSON Web Tokens (JWT)
- **Media Hosting:** Cloudinary

## 🔐 Features
- 🔒 **Authentication & Authorization** using bcrypt and JWT
- 💬 **Private 1-on-1 Chat** between users
- ⚡ **Real-time Messaging** with Socket.IO
- 🖼️ **Image Uploads** via Cloudinary
- 📜 **Persistent Chat History** with MongoDB
- 👤 **User Contacts List** to initiate conversations

## 📚 Getting Started

### 🖥️ Clone and Install

```bash
git clone https://github.com/flowz0/chat-app.git
cd chat-app
```

### ⚙️ Backend Setup
```bash
cd backend/
npm install
```

Create a `.env` file and add the following:
```bash
PORT=5001

MONGODB_URI=your_mongodb_uri

JWT_SECRET=your_jwt_secret
NODE_ENV=your_node_env

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Run the server:
```bash
npm run dev
```

### 🧑‍💻 Frontend Setup
```bash
cd frontend/
npm install
npm run dev
```

## 🙋‍♂️ Author
### Billy Flowers
- GitHub: [github.com/flows0](https://github.com/flows0)
- Portfolio: [billyf-portfolio.vercel.app](https://billyf-portfolio.vercel.app/)

## 📄 License
This project is licensed under the [MIT License](./LICENSE).