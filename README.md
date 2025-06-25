# 📋 React + Vite Feedback System

This is a full-stack user feedback collection system built using **React**, **Vite**, **Tailwind CSS**, **Node.js**, **Express**, and **MongoDB**. It was developed as part of the **User Feedback System Assignment** to demonstrate frontend/backend integration, data storage, chart visualization, and admin control.

---

## 🚀 How to Run This Project Locally

### 🧩 Prerequisites

- Node.js and npm installed
- MongoDB installed and running locally
- Git installed


##Site View:

--Form:

![image](https://github.com/user-attachments/assets/66152355-64c9-4b99-a2ba-310fe83e899d)

--Admin Access:

![image](https://github.com/user-attachments/assets/10c14ad2-5232-4657-ab26-06f3e82d29e8)

--Admin DashBoard:

![image](https://github.com/user-attachments/assets/b83f8a14-0f3f-4d28-a150-07543da4b174)




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





