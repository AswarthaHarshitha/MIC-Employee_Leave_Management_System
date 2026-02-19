# 🚀 MIC – Employee Leave Management System (MIC-ELMS)

🔗 **Live Demo:**  
https://mic-employee-leave-management-syste-ebon.vercel.app/

🔐 **Demo Credentials**
```
Email: admin@mic.edu
Password: password123
```

---

## 📌 Project Overview

MIC-ELMS is a scalable, full-stack Employee Leave Management System designed for educational institutions.  

The platform streamlines leave workflows through a structured multi-level approval system (HOD → Admin), ensuring transparency, accountability, and real-time tracking.

Built with modern web technologies, the system emphasizes security, responsiveness, and maintainable architecture.

---

## 🌟 Core Features

### 🔐 Secure Authentication & Authorization
- JWT-based authentication (HTTP-only cookies)
- Role-Based Access Control (Admin, HOD, Employee)
- Password reset functionality
- Profile management with avatar upload

### 📝 Leave Application System
- Intuitive leave request interface
- Document upload support
- Multi-level approval workflow
- Real-time leave status updates
- Leave balance tracking by category

### 🏢 Department Management
- Department-wise employee management
- HOD assignment and updates
- Department-specific leave policies

### 📊 Analytics & Reporting
- Interactive dashboard with key metrics
- Department & category-wise analytics
- Custom date range filtering
- Excel report export functionality

### 📱 Fully Responsive Design
- Optimized for Desktop, Tablet, and Mobile
- Adaptive data tables
- Mobile-first navigation
- Touch-friendly UI components

---

## 🏗️ Technical Architecture

### 🖥️ Frontend
- **React 18** (Hooks + Context API)
- **React Router v6**
- **Tailwind CSS**
- **Axios with Interceptors**
- Context-based global state management

### ⚙️ Backend
- **Node.js + Express.js**
- **MongoDB Atlas (Mongoose ODM)**
- **JWT Authentication**
- **Helmet.js (Security Headers)**
- **Rate Limiting & Input Validation**
- **Swagger API Documentation**

---

## 🔄 System Workflow

### 👩‍💼 Employee
Apply for leave → Upload documents → Track approval status

### 👨‍🏫 HOD
Review department requests → Approve or reject → Forward to Admin

### 🏢 Admin
Final approval → Manage users & departments → Generate reports

---

## 🔐 Security Implementation

- Password hashing using bcrypt
- JWT authentication with expiration
- Protected frontend & backend routes
- CORS configuration with allowed origins
- Rate limiting against brute-force attacks
- Input sanitization and validation
- Secure HTTP headers via Helmet

---

## 🚀 Installation Guide

### 1️⃣ Clone Repository
```bash
git clone https://github.com/yourusername/MIC-ELMS.git
cd MIC-ELMS
```

---

### 2️⃣ Backend Setup
```bash
cd backend
npm install
```

Create `.env` file inside backend:

```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=30d
NODE_ENV=development
CORS_ORIGIN=your_frontend_url
```

Run backend:
```bash
npm start
```

(Optional) Seed sample data:
```bash
npm run seed
```

---

### 3️⃣ Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

Create `.env` file inside frontend:

```
VITE_API_URL=your_backend_api_url
```

---

## 📡 API Structure

| Module | Endpoint |
|--------|----------|
| Authentication | `/api/auth` |
| Users | `/api/users` |
| Leaves | `/api/leaves` |
| Departments | `/api/departments` |
| Dashboard | `/api/dashboard` |
| Excel Reports | `/api/excel` |

---

## 🚢 Deployment

- **Frontend:** Vercel (Vite Production Build)
- **Backend:** Serverless-compatible configuration
- **Database:** MongoDB Atlas (Cloud)

Environment variables are securely managed for production deployment.

---

## 🛠️ Technology Stack

- React
- Node.js
- Express.js
- MongoDB
- Tailwind CSS
- JWT
- Axios
- Swagger

---

## 🎯 Resume-Ready Highlights

- Developed a full-stack leave management platform with multi-level approval logic.
- Implemented secure JWT authentication with role-based access control.
- Designed a responsive UI using Tailwind CSS.
- Built an analytics dashboard with Excel export functionality.
- Deployed production-ready application using Vercel and MongoDB Atlas.

---

## 👨‍💻 Developed By

Team MIC  
Built to modernize and simplify institutional leave management systems.
