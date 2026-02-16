# 🚖 Jeffika Cabs – Car Hire Application

Jeffika Cabs is a full-stack MERN car hire application that allows users to easily rent cars online and pay directly through the platform. The total rental cost is automatically calculated based on the number of days selected by the user.

# 📌 Features

- 🚘 Browse and hire available cars

- 📅 Rental price calculation based on number of days entered

- 💳 Payment through the application

- 🔐 User Authentication (Register & Login)

- 🧾 Secure booking system

- 📱 Responsive user-friendly interface

# 🛠 Tech Stack

This project is built using the MERN Stack:

- MongoDB – Database

- Express.js – Backend framework

- React.js – Frontend UI

- Node.js – Server environment

- Docker & Docker Compose – Containerization

# 🔐 Authentication

Jeffika Cabs includes:

- User Registration Form

- User Login Form

- Secure authentication using JWT

# 🔐 Environment Variables

# The app requires environment variables to function correctly.

- Step 1 – Create .env in server/
- server/.env
- Step 2 – Add your credentials

Use the template below. Do NOT commit this file to GitHub.

- PORT=4051
- MONGO_URI=mongodb://mongo:27017/jeffika-cabs
- JWT_SECRET=your_secret_key

- MPESA_PASSKEY=your_mpesa_passkey
- MPESA_SHORTCODE=your_shortcode
- MPESA_CONSUMER_SECRET=your_consumer_secret
- MPESA_CONSUMER_KEY=your_consumer_key
- MPESA_CALLBACK_URL=https://your-callback-url.com/api/mpesa/callback

- ADMIN_EMAIL=your_admin_email
- EMAIL_USER=your_email
- EMAIL_PASS=your_email_password

- RESEND_API_KEY=your_resend_key
# 📦 Running the App with Docker

The project is fully containerized using Docker Compose.

Requirements

- Docker

- Docker Compose

Check versions:

- docker --version
- docker-compose --version
- Step 1 – Build and Start

From the project root:

- docker-compose up --build

# This starts:

- MongoDB

- Backend server

- Frontend UI