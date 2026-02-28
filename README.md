# Freelancing Application (MERN Stack)

SB Works is a full-stack **Freelancing Web Application** developed using the **MERN stack**  
(**MongoDB, Express.js, React.js, Node.js**).

The platform connects **clients** and **freelancers**, allowing users to post projects, apply for jobs, manage applications, and collaborate efficiently.

---

## 🚀 Features

### 👤 User Authentication
- User registration and login
- Role-based access (**Client / Freelancer**)
- Secure password handling using **bcrypt**

---

### 🧑‍💼 Client Features
- Create and post freelance projects
- View all applications received for projects
- Approve or reject freelancer applications
- Track project status (Posted / Assigned / Completed)

---

### 🧑‍🎨 Freelancer Features
- View all available projects
- Apply for projects with bid amount and proposal
- View applied projects and application status
- Manage ongoing and completed projects

---

### 🌐 General Features
- Responsive and user-friendly interface
- RESTful API-based communication
- Real-time features using **Socket.IO**
- MongoDB used for persistent data storage

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
- Visual Studio Code
- Postman (API testing)

---

## 📂 Project Structure

SB-Works-Freelancing-Application-MERN
│
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── context/
│ └── styles/
│
├── server/ # Node.js backend
│ ├── Schema.js
│ ├── SocketHandler.js
│ └── index.js
│
├── screenshots/ # Application screenshots
│
└── README.md



---

## 🖼️ Application Screenshots

Screenshots of the application UI are available in the **screenshots/** folder, including:

- Landing Page  
- Login Page  
- Register Page  
- Client Dashboard  
- Client New Project Page  
- Client Applications Page  
- Freelancer Dashboard  
- Freelancer All Projects Page  
- Freelancer My Projects Page  
- Freelancer Applications Page  

---

## ⚙️ Installation & Execution Steps

1️⃣ Clone the Repository

git clone https://github.com/KrishnaVamsi28/SB-Works-Freelancing-Application-MERN.git
cd SB-Works-Freelancing-Application-MERN


2️⃣ Start Backend Server

cd server
npm install
node index.js


Backend runs on:

http://localhost:6001

3️⃣ Start Frontend

cd client
npm install
npm start


Frontend runs on:

http://localhost:3000

4️⃣ Start MongoDB

Ensure MongoDB service is running:

mongod

---

## 📌 Notes

 Admin functionality is not included in this project.

 Only Client and Freelancer roles are supported.

 Designed for academic, learning, and demonstration purposes.

---

## 👨‍💻 Developed by

 Krishna Vamsi
 GitHub: https://github.com/KrishnaVamsi28

---
