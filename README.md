# StudyNotion - EdTech Platform

A comprehensive EdTech platform built with the MERN stack that enables users to create, consume, and rate educational content.

## 🚀 Features

### Authentication & Authorization
- **User Registration & Login** - JWT-based authentication
- **OTP Verification** - Email-based OTP for secure signup
- **Password Reset** - Secure password reset functionality
- **Role-based Access** - Student and Instructor roles with different permissions

### Course Management
- **Course Creation** - Instructors can create and publish courses
- **Course Catalog** - Browse and search available courses
- **Course Details** - Detailed course information with ratings and reviews
- **Course Progress Tracking** - Track student progress through courses
- **Video Lectures** - Upload and stream video content

### User Dashboard
- **Student Dashboard** - View enrolled courses and progress
- **Instructor Dashboard** - Manage courses and view analytics
- **Profile Management** - Update personal information and preferences

### Payment Integration
- **Razorpay Integration** - Secure payment processing for course purchases
- **Order Management** - Track payment history and course purchases

### Additional Features
- **Rating & Reviews** - Students can rate and review courses
- **Contact Us** - Contact form for user inquiries
- **Responsive Design** - Mobile-friendly interface
- **File Upload** - Cloudinary integration for media uploads

## 🛠️ Technologies Used

### Frontend
- **React.js** - User interface library
- **Redux Toolkit** - State management
- **React Router** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **React Hook Form** - Form handling and validation
- **React Hot Toast** - Toast notifications
- **Axios** - HTTP client for API calls
- **Chart.js** - Data visualization for analytics
- **React Markdown** - Markdown rendering
- **Swiper.js** - Touch slider component

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - JSON Web Tokens for authentication
- **Bcrypt** - Password hashing
- **Nodemailer** - Email sending functionality
- **Multer** - File upload handling

### Third-party Services
- **MongoDB Atlas** - Cloud database hosting
- **Cloudinary** - Media storage and optimization
- **Razorpay** - Payment gateway integration
- **Gmail SMTP** - Email service for OTP delivery

### Development Tools
- **Nodemon** - Development server auto-restart
- **Concurrently** - Run multiple commands simultaneously
- **Prettier** - Code formatting
- **ESLint** - Code linting

## 📁 Project Structure

```
studynotion/
├── public/                 # Static files
├── src/                    # React frontend source
│   ├── components/         # Reusable UI components
│   ├── pages/             # Page components
│   ├── services/          # API service functions
│   ├── slices/            # Redux slices
│   ├── hooks/             # Custom React hooks
│   └── utils/             # Utility functions
├── server/                # Backend source
│   ├── controllers/       # Route controllers
│   ├── models/           # Database models
│   ├── routes/           # API routes
│   ├── middleware/       # Custom middleware
│   ├── config/           # Configuration files
│   ├── mail/             # Email templates
│   └── utils/            # Backend utilities
└── README.md
```

## 🚦 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB Atlas account
- Cloudinary account
- Razorpay account (for payments)
- Gmail account (for OTP emails)

## 🔧 Configuration

### MongoDB Atlas Setup
1. Create a MongoDB Atlas account
2. Create a new cluster
3. Add database user credentials
4. Whitelist your IP address
5. Get the connection string

### Cloudinary Setup
1. Create a Cloudinary account
2. Get your cloud name, API key, and API secret
3. Configure in environment variables

### Razorpay Setup
1. Create a Razorpay account
2. Get your key ID and key secret
3. Configure in environment variables

### Gmail SMTP Setup
1. Enable 2-factor authentication on Gmail
2. Generate an app password
3. Use app password in MAIL_PASS

## 🌐 Live Demo

- **Backend API**: https://studynotion-backend-3zcb.onrender.com
- **Frontend**: (Deploy to Netlify/Vercel for frontend)

## 🚀 Deployment

### Backend Deployment (Render)
1. Connect your GitHub repository to Render
2. Set environment variables in Render dashboard
3. Deploy with build command: `npm install`
4. Start command: `npm start`
5. **Important**: Whitelist `0.0.0.0/0` in MongoDB Atlas Network Access

### Frontend Deployment (Netlify/Vercel)
1. Build the React app: `npm run build`
2. Deploy the `build` folder
3. Set environment variable: `REACT_APP_BASE_URL=https://studynotion-backend-3zcb.onrender.com/api/v1`

## 📱 Usage

### For Students
1. **Sign up** with email verification
2. **Browse courses** in the catalog
3. **Purchase courses** using Razorpay
4. **Watch lectures** and track progress
5. **Rate and review** completed courses

### For Instructors
1. **Create instructor account**
2. **Upload course content** with videos and materials
3. **Set course pricing** and publish
4. **Monitor course analytics** and student progress
5. **Manage course content** and updates

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**MYRA JAISWAL**
- GitHub: [@MYRA31JAIS](https://github.com/MYRA31JAIS)

## 🙏 Acknowledgments

- Thanks to all the open-source libraries and tools used in this project
- Special thanks to the MERN stack community for excellent documentation
- Inspiration from various EdTech platforms

---

⭐ Star this repository if you found it helpful!