This project is a backend Node.js API server for phone number verification.
 It allows users to verify their phone numbers using an OTP (One-Time Password) sent via SMS (using Twilio SDK or any other SMS provider). 
The OTP is valid for 2 minutes and can be re-requested upon expiry.

The project demonstrates how to build a production-ready API with modular code structure, MongoDB for persistence, and JWT-based authentication, deployed on AWS API Gateway & Lambda. A minimal frontend is also provided to showcase the functionality.
🚀 Features

📦 Node.js + Express.js backend API server

🗄 MongoDB for storing user data and verification status

📲 SMS OTP delivery using Twilio SDK (or any other SMS provider)

⏱ 2-minute OTP expiry with retry option

🔐 JWT-based authentication for secured APIs

🧩 Modularized codebase with comments for maintainability

☁ Deployment on AWS Lambda & API Gateway

🌐 Minimal frontend web page to test phone verification


📂 API Endpoints

POST /send-otp → Accepts phone number, sends verification code via SMS

POST /verify-otp → Verifies the entered code and updates user status

GET /user-status → Fetch user verification status (JWT protected)


🛠 Tech Stack

Backend: Node.js, Express.js

Database: MongoDB

Auth: JWT (JSON Web Token)

SMS: Twilio SDK (or alternative)

Frontend: VITE +React
