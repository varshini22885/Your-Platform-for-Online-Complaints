# Resolve Now – Your Platform for Online Complaints

A full-stack MERN application designed to simplify the process of submitting, managing, tracking, and resolving customer complaints online. The platform improves communication between users, agents, and administrators through real-time updates and complaint management features.

**GitHub Account**: varshini22885  
**Email linked to GitHub**: varshinigeddada@gmail.com  
**Repository Name**: Your-Platform-for-Online-Complaints  

*Based on your uploaded project documentation*

## 🚀 Features
- 🔐 Secure User Authentication using JWT
- 📝 Complaint Registration System
- 📎 Multimedia Complaint Support
- 📊 Real-Time Complaint Tracking
- 💬 Chat Support Between Users & Agents
- 👨‍💼 Admin Dashboard for Complaint Management
- 🤖 Intelligent Complaint Assignment
- 🔔 Status Updates & Notifications
- 🛡️ Data Security & Confidentiality
- ⭐ Feedback & Response System

## 🛠️ Tech Stack

**Frontend**
- React.js
- Bootstrap
- Material UI
- Axios
- Socket.io Client

**Backend**
- Node.js
- Express.js
- JWT Authentication
- REST APIs
- Socket.io

**Database**
- MongoDB

## 📂 Project Structure
```
/client
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.js

/server
├── config/
├── controllers/
├── models/
├── routes/
└── server.js
```

## ⚙️ Installation & Setup

### Prerequisites
Make sure the following are installed:
- Node.js
- MongoDB
- npm
- Git

### Clone Repository
```bash
git clone https://github.com/varshini22885/Your-Platform-for-Online-Complaints.git
cd Your-Platform-for-Online-Complaints
```

### Install Dependencies

**Frontend**
```bash
cd client
npm install
```

**Backend**
```bash
cd server
npm install
```

### Environment Variables
Create a `.env` file inside the `server` folder.
```env
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000
```

## ▶️ Running the Application

**Start Backend**
```bash
cd server
npm start
```

**Start Frontend**
```bash
cd client
npm start
```

The application will run on:
- Frontend: `http://localhost:3000`
- Backend:  `http://localhost:5000`

## 🔐 Authentication
The application uses JSON Web Tokens (JWT) for authentication and authorization.
- Tokens are generated during login
- Middleware verifies tokens
- Role-based access for:
  - Admin
  - Agent
  - Customer

## 👥 User Roles

### Customer
- Register/Login
- Submit Complaints
- Track Complaint Status
- Chat with Agents

### Agent
- View Assigned Complaints
- Send Responses
- Update Complaint Status

### Admin
- Manage Users
- Assign Complaints to Agents
- Monitor Platform Activities

## 📡 API Features

**Authentication APIs**
- Register User
- Login User

**Complaint APIs**
- Register Complaint
- Fetch Complaints
- Assign Complaints
- Update Complaint Status

**Chat APIs**
- Send Messages
- Retrieve Chat History

## 🧪 Testing
- API Testing using Postman
- Frontend Testing through UI interactions
- Unit Testing can be extended using:
  - Jest
  - Mocha

## ⚠️ Known Issues
- WebRTC video chat may not work in some browsers
- Email delivery can delay during heavy traffic
- UI responsiveness may slow on poor network conditions

## 🔮 Future Enhancements
- Advanced Analytics Dashboard
- Complaint Categories & SLA Monitoring
- WhatsApp/SMS Notifications
- Granular Role-Based Access Control
- Multilingual User Interface

## 🎥 Demo
**Video Demo Link**: [Google Drive Link](https://drive.google.com/file/d/1sYFgYx5FWyvRVqjwKXv5UU_NZp5jhAql/view?usp=sharing)

## 👨‍💻 Team Members
- **Sri Varshini** – Frontend & Backend Development

## 📜 License
This project is developed for educational and learning purposes.

## 💡 About the Project
Resolve Now aims to provide a transparent and efficient complaint resolution system where customers can easily submit complaints, track progress, and communicate directly with support agents in real time. The platform improves customer satisfaction while helping organizations manage complaints effectively.

