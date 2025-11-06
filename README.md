# StudyNotion Edtech Project
Project Overview

StudyNotion is a full-stack EdTech platform built to simplify online education by connecting instructors and learners in one place.
It enables instructors to create, manage, and sell online courses, while students can browse, purchase, and learn through an interactive dashboard.

Features
 For Instructors

  Create and publish new courses with title, description, and media.
  
  Upload video lectures, PDFs, and other learning materials.
  
  Manage course content, pricing, and students.
  
  Track course performance and earnings.
For Students

  Browse available courses and purchase securely.
  
  Access enrolled courses through a personalized dashboard.
  
  Stream video lessons and track learning progress.
  
  Get completion certificates (optional feature).

Authentication & Authorization

  Secure login/signup using JWT and bcrypt.
  
  Role-based access control (Admin / Instructor / Student).

Payment Integration

  Integrated with Razorpay for secure payment processing.

Additional Features

  Contact form with backend email handling (using Nodemailer).
  
  Secure cookies & session management with cookie-parser.
  
  Responsive front-end for mobile and desktop.

Tech Stack

    Frontend: React.js, TailwindCSS, Redux
    Backend: Node.js, Express.js
    Database: MongoDB (Mongoose ORM)
    Authentication: JWT, bcrypt, cookie-parser
    Payment Gateway: Razorpay API
    Cloud Storage: Cloudinary (for media upload)
    Other Tools: dotenv, CORS, Nodemailer

Architecture

  The project follows the MVC (Model-View-Controller) pattern:
  
  Model: MongoDB schemas for users, courses, and payments
  
  View: React components for UI rendering
  
  Controller: Express route handlers for API logic
  
 Results and Discussions
    <img width="1512" height="847" alt="image" src="https://github.com/user-attachments/assets/1e9ec8ca-1f33-4e40-b6de-44dc5f61f48a" />
    <img width="1512" height="847" alt="image" src="https://github.com/user-attachments/assets/249ee839-f1cb-45c5-986b-3e1f0e73ea0c" />
    <img width="1512" height="847" alt="image" src="https://github.com/user-attachments/assets/a1222e47-2d30-46f3-a70c-bd72709a8e48" />
    <img width="1512" height="847" alt="image" src="https://github.com/user-attachments/assets/4645ecd3-7afa-4bd2-9e3a-43e2fcf98da1" />




    

Future Scope
This section discusses potential future improvements to the StudyNotion platform. These
enhancements are listed along with an explanation of how they would improve the platform
and priority for implementation.

• Gamification features: Adding gamification features such as badges, points, and
leaderboards can increase user engagement and motivation. This would be a medium-
priority enhancement.

• Personalized learning paths: Creating personalized learning paths for each student
based on their interests and learning style can increase student satisfaction and
success. This would be a high-priority enhancement.

• Social learning features: Adding social learning features such as group discussions,
peer-to-peer feedback, and collaborative projects can increase student engagement
and interaction. This would be a medium-priority enhancement.

• Mobile app: Creating a mobile app for the platform would allow for more convenient
access to course content and features, and would increase the platform's reach. This
would be a high-priority enhancement.

• Machine learning-powered recommendations: Using machine learning algorithms to
provide personalized course recommendations can improve student engagement and
satisfaction. This would be a medium to high-priority enhancement

Installation & Setup
  # Clone the repository
  git clone https://github.com/DsinghZGit/StudyNotion.git
  
  # Navigate to server folder
  cd server
  
  # Install dependencies
  npm install
  
  # Add environment variables in .env
  MONGO_URI=...
  JWT_SECRET=...
  RAZORPAY_KEY=...
  
  # Run the backend
  npm run dev
