# **RizeHire – AI Powered Job Portal**

RizeHire is a **full-stack job portal** built using the **MERN stack** that allows job seekers and recruiters to connect through secure authentication, intelligent job matching, and online payments.

---

## 📋 Features

🔐 **Authentication & Authorization**
JWT-based login and role-based access for **Job Seekers** and **Job Posters**

💼 **Job Management**
Recruiters can post, update, and delete job listings

🎯 **Smart Job Matching**
Users can search and apply for jobs based on skills and preferences

📄 **Resume Upload & Profile Management**
Candidates can upload resumes and manage their profiles

💳 **Razorpay Payments**
Secure payments for premium job posting and subscriptions

📊 **Application Tracking**
Candidates can track application status

---

## 🛠 Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication
* Razorpay Payment Gateway

---

## 📦 Prerequisites

Make sure you have installed:

* Node.js (v18 or above)
* MongoDB (Local or Atlas)
* Git

---

## 🚀 Local Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/RizeHire.git
cd RizeHire
```

---

## 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside `backend` folder:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
```

Start backend server:

```bash
npm run dev
```

Backend runs on:
**[http://localhost:5000](http://localhost:5000)**

---

## 3️⃣ Frontend Setup

```bash
cd client
npm install
```

Create `.env` inside `client`:

```env
REACT_APP_API_URL=http://localhost:5000/api
```

Start frontend:

```bash
npm start
```

Frontend runs on:
**[http://localhost:3000](http://localhost:3000)**

---

## 🧩 Project Structure

```
RizeHire/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── client/
│   ├── src/
│   ├── components/
│   └── pages/
│
└── README.md
```

---

## 🔌 API Endpoints

### Authentication

| Method | Endpoint           | Description   |
| ------ | ------------------ | ------------- |
| POST   | /api/auth/register | Register user |
| POST   | /api/auth/login    | Login         |
| POST   | /api/auth/logout   | Logout        |

### Jobs

| Method | Endpoint      | Description  |
| ------ | ------------- | ------------ |
| GET    | /api/jobs     | Get all jobs |
| POST   | /api/jobs     | Create job   |
| PUT    | /api/jobs/:id | Update job   |
| DELETE | /api/jobs/:id | Delete job   |

### Applications

| Method | Endpoint          | Description         |
| ------ | ----------------- | ------------------- |
| POST   | /api/applications | Apply for job       |
| GET    | /api/applications | Get my applications |

---

## 👨‍💻 Author

**Sachin Kumar**
📧 Email: **[sachinyadav887780@gmail.com](mailto:sachinyadav887780@gmail.com)**

---

## 📜 License

This project is licensed under the **MIT License**.
 
