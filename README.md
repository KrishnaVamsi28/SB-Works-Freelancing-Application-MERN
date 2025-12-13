# SB Works – Freelancing Application (MERN Stack)

SB Works is a full-stack **Freelancing Web Application** developed using the **MERN stack** (MongoDB, Express.js, React.js, Node.js).  
The platform connects **freelancers** and **clients**, allowing users to post projects, apply for jobs, manage profiles, and collaborate efficiently.

---

## 🚀 Features

### 👤 User Authentication
- User registration and login
- Role-based access (Client / Freelancer)
- Secure authentication using JWT

### 🧑‍💼 Client Features
- Post freelance projects
- View freelancer applications
- Manage posted projects

### 🧑‍🎨 Freelancer Features
- Browse available projects
- Apply for freelance jobs
- Manage freelancer profile

### 🌐 General Features
- Responsive user interface
- RESTful API integration
- MongoDB database for data persistence

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB (Community Server)

### Tools & Platforms
- MongoDB Compass
- Git & GitHub
- Visual Studio Code / IntelliJ IDEA
- Postman (for API testing)

---

## 📂 Project Structure

SB-Works-Freelancing-Application-MERN
│
├── client/ # React frontend
│ ├── public/
│ └── src/
│
├── server/ # Node.js backend
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ └── index.js
│
└── README.md 



---

## ⚙️ Installation & Execution Steps

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/KrishnaVamsi28/SB-Works-Freelancing-Application-MERN.git
cd SB-Works-Freelancing-Application-MERN


2️⃣ Start Backend Server
cd server
npm install
node index.js

Backend runs on:
http://localhost:5000


3️⃣ Start Frontend
cd client
npm install
npm start

Frontend runs on:
http://localhost:3000


4️⃣ Start MongoDB
Ensure MongoDB service is running:
mongod
