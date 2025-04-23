website link: https://secure-e-commerce-website-design-frontend.vercel.app/

This is a full-stack e-learning platform (Learn2Play)consisting of:
Frontend – Built with React.js + Vite
Backend – Built with Node.js + Express
Database – MongoDB

Prerequisites
Ensure you have the following installed:
Node.js
npm
MongoDB (local or cloud e.g., MongoDB Atlas)

Gitgit clone https://github.com/Rachana1646/secure-ecommerce.git
cd secure-ecommerce

In the vscode terminal
cd frontend
npm install
npm run dev

take the new terminal
cd server
npm install
npm start

**Features**
User-Friendly UI: Students can register, make payments, and access courses easily.

 Role-Based Access:

Student Dashboard – Enroll in and track progress in lectures

Admin Dashboard – Create, update, or delete courses

 Secure Payments: Handled with Stripe API

 Email Verification: Users receive OTP verification emails

 CAPTCHA & JWT: CAPTCHA for bot protection & JWT tokens for session security

 Progress Tracking: Real-time updates on lecture completion and dashboard insights


 **Security Measures**

 Email OTP verification during signup

 CAPTCHA integration to prevent bot signups

 JWT token-based authentication

 CORS setup & HTTPS headers

 Vulnerability scanning with Wapiti and OWASP ZAP


 







