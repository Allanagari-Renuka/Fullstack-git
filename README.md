<div align="center">

# 🚀 Full Stack Web Application

### Modern MERN Stack Project with Complete Frontend & Backend

[![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6.0+-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/Express.js-4.18+-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**A full-featured web application built with the MERN stack, featuring user authentication, RESTful API, responsive design, and modern development practices**

[Features](#-features) • [Demo](#-live-demo) • [Installation](#-installation) • [API Documentation](#-api-documentation) • [Tech Stack](#-tech-stack)

---

![Application Banner](https://via.placeholder.com/1000x400/61DAFB/000000?text=Add+Your+Application+Banner+Here)

</div>

---

## 📌 Overview

This **Full Stack Web Application** demonstrates modern web development practices using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The application features a robust backend API, interactive frontend interface, secure authentication, and real-time data management.

### 🎯 Key Highlights

- 🔐 **Secure Authentication** - JWT-based user authentication and authorization
- 🎨 **Modern UI/UX** - Responsive design with React and modern CSS frameworks
- 🚀 **RESTful API** - Well-structured backend with Express.js
- 💾 **Database Integration** - MongoDB for scalable data storage
- ⚡ **Real-Time Updates** - Dynamic content updates without page refresh
- 📱 **Mobile Responsive** - Optimized for all device sizes
- 🔒 **Security First** - Input validation, sanitization, and secure practices

---

## ✨ Features

### User Features
- ✅ **User Registration & Login** - Secure account creation with email verification
- ✅ **Profile Management** - Update user information and preferences
- ✅ **Dashboard** - Personalized user dashboard with analytics
- ✅ **CRUD Operations** - Create, Read, Update, Delete functionality
- ✅ **Search & Filter** - Advanced search with multiple filters
- ✅ **Pagination** - Efficient data loading with pagination
- ✅ **File Upload** - Image/document upload with validation
- ✅ **Notifications** - Real-time alerts and notifications

### Technical Features
- 🔐 JWT Authentication with refresh tokens
- 📊 RESTful API with proper HTTP methods
- 🛡️ Input validation and sanitization
- 🔄 Error handling and logging
- 📱 Responsive design (Mobile, Tablet, Desktop)
- ⚡ Optimized performance with lazy loading
- 🎨 Modern UI with Tailwind CSS / Bootstrap
- 🔍 SEO-friendly structure

---

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Redux](https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/-Mongoose-880000?style=flat-square&logo=mongodb&logoColor=white)

### Authentication & Security
![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)
![bcrypt](https://img.shields.io/badge/-bcrypt-338033?style=flat-square)

### Tools & Deployment
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Heroku](https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## 🚀 Live Demo

### 🌐 Application Links
- **Frontend:** [https://your-frontend.vercel.app](https://your-frontend.vercel.app)
- **Backend API:** [https://your-backend.herokuapp.com](https://your-backend.herokuapp.com)

### Demo Credentials
```
Email: demo@example.com
Password: Demo@123
```

---

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

```bash
Node.js >= 14.x
MongoDB >= 4.x
npm or yarn
Git
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Allanagari-Renuka/Fullstack-git.git
cd Fullstack-git
```

### 2️⃣ Backend Setup

```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create .env file
cat > .env << EOF
PORT=5000
MONGODB_URI=mongodb://localhost:27017/your-database
JWT_SECRET=your_jwt_secret_key_here
JWT_EXPIRE=7d
NODE_ENV=development
EOF

# Start the backend server
npm run dev
```

Backend will run on `http://localhost:5000`

### 3️⃣ Frontend Setup

```bash
# Navigate to frontend directory (in a new terminal)
cd frontend

# Install dependencies
npm install

# Create .env file
cat > .env << EOF
REACT_APP_API_URL=http://localhost:5000/api
EOF

# Start the frontend application
npm start
```

Frontend will run on `http://localhost:3000`

---

## 📁 Project Structure

```
Fullstack-git/
│
├── frontend/                 # React frontend
│   ├── public/              # Public assets
│   ├── src/
│   │   ├── components/      # Reusable components
│   │   │   ├── Auth/
│   │   │   ├── Dashboard/
│   │   │   ├── Layout/
│   │   │   └── Common/
│   │   ├── pages/           # Page components
│   │   │   ├── Home.js
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   └── Dashboard.js
│   │   ├── services/        # API services
│   │   │   └── api.js
│   │   ├── context/         # Context API
│   │   │   └── AuthContext.js
│   │   ├── utils/           # Utility functions
│   │   ├── App.js           # Main App component
│   │   └── index.js         # Entry point
│   ├── package.json
│   └── .env
│
├── backend/                 # Node.js/Express backend
│   ├── config/             # Configuration files
│   │   ├── db.js           # Database connection
│   │   └── config.js       # App configuration
│   ├── controllers/        # Route controllers
│   │   ├── authController.js
│   │   └── userController.js
│   ├── models/             # Mongoose models
│   │   ├── User.js
│   │   └── Post.js
│   ├── routes/             # API routes
│   │   ├── auth.js
│   │   └── users.js
│   ├── middleware/         # Custom middleware
│   │   ├── auth.js
│   │   ├── error.js
│   │   └── validation.js
│   ├── utils/              # Utility functions
│   │   └── helpers.js
│   ├── server.js           # Entry point
│   ├── package.json
│   └── .env
│
├── README.md               # Project documentation
├── .gitignore             # Git ignore file
└── LICENSE                # License file
```

---

## 🔌 API Documentation

### Base URL
```
http://localhost:5000/api
```

### Authentication Endpoints

#### Register User
```http
POST /api/auth/register
Content-Type: application/json

{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "Password@123"
}
```

**Response (201 Created):**
```json
{
  "success": true,
  "message": "User registered successfully",
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "user": {
    "id": "507f1f77bcf86cd799439011",
    "name": "John Doe",
    "email": "john@example.com"
  }
}
```

#### Login User
```http
POST /api/auth/login
Content-Type: application/json

{
  "email": "john@example.com",
  "password": "Password@123"
}
```

**Response (200 OK):**
```json
{
  "success": true,
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "user": {
    "id": "507f1f77bcf86cd799439011",
    "name": "John Doe",
    "email": "john@example.com"
  }
}
```

### Protected Routes

#### Get Current User
```http
GET /api/auth/me
Authorization: Bearer {token}
```

#### Update User Profile
```http
PUT /api/users/:id
Authorization: Bearer {token}
Content-Type: application/json

{
  "name": "John Updated",
  "email": "john.updated@example.com"
}
```

### Error Responses

```json
{
  "success": false,
  "message": "Error message here",
  "error": "Detailed error information"
}
```

---

## 💻 Usage Examples

### Frontend API Integration

```javascript
// services/api.js
import axios from 'axios';

const API_URL = process.env.REACT_APP_API_URL;

// Create axios instance
const api = axios.create({
  baseURL: API_URL,
  headers: {
    'Content-Type': 'application/json'
  }
});

// Add token to requests
api.interceptors.request.use(
  (config) => {
    const token = localStorage.getItem('token');
    if (token) {
      config.headers.Authorization = `Bearer ${token}`;
    }
    return config;
  },
  (error) => Promise.reject(error)
);

// Auth service
export const authService = {
  register: (userData) => api.post('/auth/register', userData),
  login: (credentials) => api.post('/auth/login', credentials),
  getCurrentUser: () => api.get('/auth/me')
};

export default api;
```

### Backend Controller Example

```javascript
// controllers/authController.js
const User = require('../models/User');
const jwt = require('jsonwebtoken');

// Register user
exports.register = async (req, res) => {
  try {
    const { name, email, password } = req.body;

    // Check if user exists
    const existingUser = await User.findOne({ email });
    if (existingUser) {
      return res.status(400).json({
        success: false,
        message: 'User already exists'
      });
    }

    // Create user
    const user = await User.create({ name, email, password });

    // Generate token
    const token = jwt.sign(
      { id: user._id },
      process.env.JWT_SECRET,
      { expiresIn: process.env.JWT_EXPIRE }
    );

    res.status(201).json({
      success: true,
      token,
      user: {
        id: user._id,
        name: user.name,
        email: user.email
      }
    });
  } catch (error) {
    res.status(500).json({
      success: false,
      message: 'Server error',
      error: error.message
    });
  }
};
```

---

## 🎨 Screenshots

<div align="center">

### Landing Page
![Landing Page](screenshots/landing.png)

### Login & Registration
![Auth Pages](screenshots/auth.png)

### User Dashboard
![Dashboard](screenshots/dashboard.png)

### Mobile Responsive
![Mobile View](screenshots/mobile.png)

</div>

---

## 🚀 Deployment

### Deploy Frontend to Vercel

1. **Install Vercel CLI:**
```bash
npm install -g vercel
```

2. **Deploy:**
```bash
cd frontend
vercel
```

### Deploy Backend to Heroku

1. **Create Heroku App:**
```bash
heroku create your-app-name
```

2. **Set Environment Variables:**
```bash
heroku config:set MONGODB_URI=your_mongodb_uri
heroku config:set JWT_SECRET=your_jwt_secret
```

3. **Deploy:**
```bash
git push heroku main
```

### Deploy with Docker

**docker-compose.yml:**
```yaml
version: '3.8'

services:
  backend:
    build: ./backend
    ports:
      - "5000:5000"
    environment:
      - MONGODB_URI=mongodb://mongo:27017/myapp
      - JWT_SECRET=your_secret
    depends_on:
      - mongo

  frontend:
    build: ./frontend
    ports:
      - "3000:3000"
    environment:
      - REACT_APP_API_URL=http://localhost:5000/api

  mongo:
    image: mongo:latest
    ports:
      - "27017:27017"
    volumes:
      - mongo-data:/data/db

volumes:
  mongo-data:
```

**Run with Docker:**
```bash
docker-compose up -d
```

---

## 🧪 Testing

### Backend Tests
```bash
cd backend
npm test
```

### Frontend Tests
```bash
cd frontend
npm test
```

### Run Coverage
```bash
npm run test:coverage
```

---

## 🔒 Security Best Practices

- ✅ **Password Hashing** - bcrypt with salt rounds
- ✅ **JWT Tokens** - Secure token generation and validation
- ✅ **Input Validation** - Using express-validator
- ✅ **CORS Configuration** - Controlled cross-origin requests
- ✅ **Rate Limiting** - Prevent brute force attacks
- ✅ **Helmet.js** - Secure HTTP headers
- ✅ **MongoDB Injection Prevention** - Using Mongoose sanitization
- ✅ **XSS Protection** - Content Security Policy

---

## 🎯 Key Achievements

- ✅ Built complete full-stack application with MERN stack
- ✅ Implemented secure JWT authentication system
- ✅ Created responsive UI with modern design principles
- ✅ Developed RESTful API with proper HTTP methods
- ✅ Integrated MongoDB for scalable data storage
- ✅ Deployed application to production (Vercel + Heroku)
- ✅ Implemented error handling and validation
- ✅ Added real-time features and notifications

---

## 🔮 Future Enhancements

- [ ] **Real-time Chat** - WebSocket integration with Socket.io
- [ ] **Email Notifications** - SendGrid/Nodemailer integration
- [ ] **Payment Gateway** - Stripe/PayPal integration
- [ ] **Admin Dashboard** - Advanced analytics and management
- [ ] **Social Authentication** - Google, Facebook, GitHub login
- [ ] **File Storage** - AWS S3 or Cloudinary integration
- [ ] **Testing** - Jest and React Testing Library
- [ ] **CI/CD Pipeline** - GitHub Actions automation
- [ ] **Docker Support** - Containerization for easy deployment
- [ ] **API Documentation** - Swagger/OpenAPI integration
- [ ] **Progressive Web App** - PWA features
- [ ] **Internationalization** - Multi-language support

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**
2. **Create your feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Coding Standards
- Follow ESLint configuration
- Write meaningful commit messages
- Add tests for new features
- Update documentation

---

## 📝 Environment Variables

### Backend (.env)
```env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/your-database
JWT_SECRET=your_super_secret_key_here
JWT_EXPIRE=7d
NODE_ENV=development
FRONTEND_URL=http://localhost:3000
```

### Frontend (.env)
```env
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_ENV=development
```

---

## 🐛 Known Issues

- [ ] Issue #1: Description
- [ ] Issue #2: Description

View all [open issues](https://github.com/Allanagari-Renuka/Fullstack-git/issues)

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Allanagari Renuka**

Full Stack Developer | MERN Stack Specialist | Building Scalable Web Applications

- 🌐 **Portfolio:** [portfolio-beige-two-49.vercel.app](https://portfolio-beige-two-49.vercel.app/)
- 💼 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/allanagari-renuka-8a9346263/)
- 📧 **Email:** [allanagarirenuka28@gmail.com](mailto:allanagarirenuka28@gmail.com)
- 🐙 **GitHub:** [@Allanagari-Renuka](https://github.com/Allanagari-Renuka)

---

## 🙏 Acknowledgments

- [React Documentation](https://reactjs.org/)
- [Node.js Documentation](https://nodejs.org/)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Express.js Documentation](https://expressjs.com/)
- Open source community

---

## 📞 Support

Need help? Here's how to reach out:

- 🐛 **Bug Reports:** [Open an issue](https://github.com/Allanagari-Renuka/Fullstack-git/issues)
- 💡 **Feature Requests:** [Submit a request](https://github.com/Allanagari-Renuka/Fullstack-git/issues)
- 📧 **Email:** allanagarirenuka28@gmail.com

---

## 📊 Project Status

![GitHub last commit](https://img.shields.io/github/last-commit/Allanagari-Renuka/Fullstack-git)
![GitHub issues](https://img.shields.io/github/issues/Allanagari-Renuka/Fullstack-git)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Allanagari-Renuka/Fullstack-git)
![GitHub repo size](https://img.shields.io/github/repo-size/Allanagari-Renuka/Fullstack-git)

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

![Made with React](https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Made with Node.js](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Database MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Building the future, one commit at a time! 🚀**

</div>
