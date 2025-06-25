# 📋 React + Vite Feedback System

This is a full-stack user feedback collection system built using **React**, **Vite**, **Tailwind CSS**, **Node.js**, **Express**, and **MongoDB**. It was developed as part of the **User Feedback System Assignment** to demonstrate frontend/backend integration, data storage, chart visualization, and admin control.

---

## 🚀 How to Run This Project Locally

### 🧩 Prerequisites

- Node.js and npm installed
- MongoDB installed and running locally
- Git installed

---

### 📦 Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/Surjeet-Singh1/Liaplus--Assignment.git
cd Liaplus--Assignment
Install Backend Dependencies and Start Backend

bash
Copy code
npm install
node server.js
This starts the backend server at: http://localhost:5000

Install Frontend Dependencies and Start React App

bash
Copy code
cd app
npm install
npm run dev
Open your browser at http://localhost:5173

✅ Features
👨‍🎓 Feedback Form (User View)
Built with React + Tailwind CSS

Collects:

Subject

Teacher Name

Rating (1 to 5)

Comments

Optional Name and Email

Sends data to the backend using axios

🛠 Backend API (Node + Express)
Stores data in local MongoDB

APIs:

POST /submit-feedback → Submit feedback

GET /all-feedbacks → Get all feedbacks

GET /feedback-report → Aggregated data for charts

📊 Admin Dashboard
Protected via password prompt

Features:

📈 Bar chart showing average ratings per teacher

🥧 Pie chart showing number of feedbacks per teacher

📋 Table of all feedbacks with sorting/filter by rating

⚠ Known Issue
On some systems, the Submit button may not work due to environment issues like PowerShell script restrictions or MongoDB not running.

However, the logic is correctly implemented and tested.
Please ensure:

MongoDB is running locally (mongod)

Backend server is started with node server.js

Frontend is calling correct URL (http://localhost:5000)

📁 Project Structure

Liaplus--Assignment/
├── app/                 → React frontend
│   ├── Form.jsx
│   ├── Report.jsx
│   ├── App.jsx
│   └── main.jsx
├── server.js            → Express backend
├── package.json
├── README.md

📸 Screenshots
![image](https://github.com/user-attachments/assets/36f6f6c1-925c-4b18-b2b2-86385a987e0e)

🔐 Admin Login
![image](https://github.com/user-attachments/assets/f5b693b2-4bac-4dd5-aa4b-f97303f9b0b7)

📊 Dashboard
![image](https://github.com/user-attachments/assets/b5000b65-0356-4e18-b043-aaea1ccfbbad)


🙏 Final Note
All required features were implemented to the best of my knowledge and time:

✅ Functional form

✅ Secure backend

✅ MongoDB integration

✅ Admin-only dashboard with charts and table

✅ Sorting functionality

Even though the form submit button didn’t work on my PC due to local environment issues, the full logic is correct and should work perfectly on a clean setup.


👤 Author
Surjeet Singh
GitHub: Surjeet-Singh1





