# 📚 StudyBuddy — Study Group Scheduler

StudyBuddy is a full-stack web application that helps students create and manage study groups. Users can schedule study sessions, invite friends, and track upcoming events — all in one place.

---

## 🚀 Features

- ✅ **User Registration & Login**
- 👥 **Create & Join Study Groups**
- 📅 **Schedule Study Sessions**
- 🗓️ **Calendar View of Upcoming Events**
- 🔗 **Invite Members via Link**
- 🗨️ **(Optional) Real-time Group Chat**
- 🔄 **(Optional) Google Calendar Sync**
- 🎨 **Responsive & Clean UI**

---

## 🛠 Tech Stack

| Frontend        | Backend         | Database    | Extras                        |
|------------------|------------------|-------------|-------------------------------|
| React.js         | Node.js + Express| MongoDB     | JWT Auth, Socket.io (chat)    |
| Tailwind CSS     | REST API         | Mongoose    | Google Calendar API (optional)|
| Axios            | Bcrypt           |             | Vercel / Render (deployment)  |

---

## 🗂 Folder Structure:

studybuddy/
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── services/
│ ├── App.js
│ └── index.js
├── server/ # Express backend
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── index.js
├── .gitignore
├── README.md
└── package.json


---

## 📦 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/studybuddy.git
cd studybuddy


2. Install Dependencies
Backend
 - cd server
 - npm install

Frontend
 - cd ../client
 - npm install

🔐 Environment Variables
In the /server folder, create a .env file with:
PORT=5000
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret_key

🧪 Running the App
Start Backend
  - cd server
  - npm run dev

Start Frontend
  - cd client
  - npm start

🎯 Core Features Breakdown
🔐 Authentication
Secure user login/registration with JWT

Role-based access (admin of group vs member)

📅 Group & Session Management
Users can create groups and become group admins

Admins can schedule sessions with title, date, time, description

Other users can join via group link

📆 Calendar View
See all upcoming sessions in a simple list or full calendar format

Filters by date or group

🔗 Invites
Copyable invite link

Optional: invite by email

🔄 Optional Features
Chat: Real-time messaging using Socket.io 

Google Calendar: Sync study events


Authors @Naqeeb Ahmadzai and @Alina Salam <3
