# HealthBooker 🏥

## Overview
HealthBooker is a comprehensive healthcare appointment booking system built with the MERN stack (MongoDB, Express.js, React.js, Node.js). The platform enables seamless interaction between patients and healthcare providers, featuring real-time appointment management and secure authentication.

## Features
- 👤 **User Authentication & Authorization**
  - Secure login/signup with JWT
  - Role-based access control (Patient/Doctor/Admin)

- 🏥 **For Patients**
  - Browse available doctors
  - Book and manage appointments
  - Receive real-time notifications
  - Update profile information

- 👨‍⚕️ **For Doctors**
  - Manage appointments
  - Update availability
  - Profile management

- 👨‍💼 **Admin Dashboard**
  - Approve doctor applications
  - Manage users and appointments
  - System-wide monitoring

## Technology Stack

### Frontend
- React.js
- HTML5 & CSS3
- JavaScript

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- JWT Authentication

### Additional Features
- Real-time notifications
- RESTful API architecture
- Secure data handling

## Getting Started

### Prerequisites
- Node.js
- MongoDB Atlas account
- npm/yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install dependencies for backend
```bash
npm install
```

3. Install dependencies for frontend
```bash
cd client
npm install
```

4. Create .env file in root directory
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

5. Start the server
```bash
npm start
```

6. Start the client
```bash
cd client
npm start
```

## Admin Access
1. Register as a normal user
2. Access MongoDB database
3. Change the user's 'isAdmin' field to 'true'
4. Log in with the same credentials

## Project Status
🟢 Active & Maintained
