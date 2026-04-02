# Repo Hub: Collaborative Code Management 🚀

A full-stack GitHub-like platform that allows developers to manage repositories, collaborate, and authenticate using GitHub OAuth.

---

## 📌 Features

* 🔐 Authentication using GitHub OAuth (Passport.js)
* 📁 Create, update, and delete repositories
* 👥 Collaborate with other users
* 🌐 REST API integration with GitHub
* 💻 Clean and responsive UI using Tailwind CSS
* ⚡ Fast and scalable MERN stack architecture

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* GitHub OAuth
* Passport.js

### Tools & APIs

* GitHub REST API
* Postman (API testing)
* Visual Studio Code
* Git & GitHub

---

## 📂 Project Structure

```
repo-hub/
│
├── client/          # React frontend
├── server/          # Node.js backend
├── models/          # MongoDB schemas
├── routes/          # API routes
├── controllers/     # Logic for routes
├── config/          # OAuth & DB config
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/repo-hub.git
cd repo-hub
```

### 2. Install dependencies

#### Backend

```
cd server
npm install
```

#### Frontend

```
cd client
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the server folder:

```
MONGO_URI=your_mongodb_connection
GITHUB_CLIENT_ID=your_client_id
GITHUB_CLIENT_SECRET=your_client_secret
SESSION_SECRET=your_secret_key
```

---

## ▶️ Running the App

### Start Backend

```
cd server
npm run dev
```

### Start Frontend

```
cd client
npm start
```





