# 🏨 Hotel Booking Application

A full-stack hotel booking web application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This application allows users to browse available rooms, check details, make bookings, and manage reservations through an intuitive and responsive interface.

---

## 🚀 Features

- 🔐 User authentication (Login/Signup)
- 🏘️ Browse and filter available rooms
- 🗓️ Book rooms with date selection
- 🧾 Booking history and management
- 💻 Responsive UI with smooth navigation
- 📦 RESTful API integration between frontend and backend
- 🗃️ MongoDB for storing users, rooms, and bookings

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Bootstrap / CSS
- Axios

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB
- Mongoose ODM

**Tools:**
- Git & GitHub
- Visual Studio Code
- Postman (for API testing)

---

## 🧪 How to Run Locally

### 🔧 Prerequisites
- Node.js and npm installed
- MongoDB running locally or Atlas connection
- Git

### 🔹 Clone the Repo

git clone https://github.com/Sidramyyavb12/Hotel-booking-application.git
cd Hotel-booking-application

🔹 2. Install Dependencies
Backend
cd backend
npm install
Frontend
cd ../frontend
npm install

🔹 3. Set Up Environment Variables
Create a .env file in the backend/ folder and add the following:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

🔹 4. Start the Application
Start Backend

cd backend
npm run dev

Start Frontend

cd ../frontend
npm start
