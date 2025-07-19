# DevTech - Online Learning Platform

A comprehensive e-learning platform built with React.js and Node.js, designed to provide high-quality coding education and skill development courses.

## 🚀 Live Demo

**Frontend:** [https://dev-tech-pink.vercel.app](https://dev-tech-pink.vercel.app)

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [Contact](#contact)

## ✨ Features

### For Students
- **User Authentication** - Secure signup/login with OTP verification
- **Course Catalog** - Browse and enroll in various coding courses
- **Interactive Learning** - Video lectures, quizzes, and hands-on projects
- **Progress Tracking** - Monitor learning progress and achievements
- **Payment Integration** - Secure course purchases via Razorpay
- **User Dashboard** - Personalized learning dashboard
- **Reviews & Ratings** - Rate and review courses

### For Instructors
- **Course Creation** - Create and manage courses with sections and subsections
- **Content Upload** - Upload videos, documents, and other learning materials
- **Student Analytics** - Track student progress and engagement
- **Revenue Dashboard** - Monitor earnings and course performance

### General Features
- **Responsive Design** - Works seamlessly on all devices
- **Email Notifications** - Automated emails for various actions
- **Contact Form** - Get in touch with support team
- **Search & Filter** - Find courses easily
- **Dark Theme** - Modern UI with Tailwind CSS

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI library
- **Redux Toolkit** - State management
- **React Router** - Navigation
- **Tailwind CSS** - Styling
- **React Hook Form** - Form handling
- **React Hot Toast** - Notifications
- **Axios** - HTTP client

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM
- **JWT** - Authentication
- **Bcrypt** - Password hashing
- **Nodemailer** - Email service
- **Cloudinary** - Media storage
- **Razorpay** - Payment gateway

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Git

### Clone the repository
```bash
git clone https://github.com/DevvratSharma026/DevTech-Hosting.git
cd DevTech-Hosting
```

### Install Frontend Dependencies
```bash
npm install
```

### Install Backend Dependencies
```bash
cd server
npm install
```

## 🔧 Environment Variables

### Frontend (.env)
```env
REACT_APP_BASE_URL=http://localhost:4000/api/v1
```

### Backend (server/.env)
```env
MONGODB_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
MAIL_HOST=smtp.gmail.com
MAIL_USER=your_email@gmail.com
MAIL_PASS=your_email_password
RAZORPAY_KEY=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret
CLOUD_NAME=your_cloudinary_cloud_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
FOLDER_NAME=your_cloudinary_folder_name
PORT=4000
```

## 🚀 Usage

### Development Mode

1. **Start the backend server:**
```bash
cd server
npm run dev
```

2. **Start the frontend development server:**
```bash
npm start
```

3. **Run both concurrently:**
```bash
npm run dev
```

### Production Build
```bash
npm run build
```

## 🔗 API Endpoints

### Authentication
- `POST /api/v1/auth/signup` - User registration
- `POST /api/v1/auth/login` - User login
- `POST /api/v1/auth/sendotp` - Send OTP for verification

### Courses
- `GET /api/v1/course/getAllCourses` - Get all courses
- `POST /api/v1/course/createCourse` - Create new course
- `PUT /api/v1/course/editCourse` - Edit course
- `DELETE /api/v1/course/deleteCourse` - Delete course

### Sections
- `POST /api/v1/course/addSection` - Create section
- `PUT /api/v1/course/updateSection` - Update section
- `DELETE /api/v1/course/deleteSection` - Delete section

### Payments
- `POST /api/v1/payment/capturePayment` - Process payment
- `POST /api/v1/payment/verifyPayment` - Verify payment

### Contact
- `POST /api/v1/reach/contact` - Contact form submission

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

**Developer:** Devvrat Sharma  
**Email:** devsharma.pcm.2003@gmail.com  
**GitHub:** [@DevvratSharma026](https://github.com/DevvratSharma026)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to all contributors who helped build this platform
- Special thanks to the open-source community for the amazing tools and libraries
- Inspired by modern e-learning platforms and educational technology

---

⭐ **Star this repository if you found it helpful!**
