# SwaAdhyaya LMS

## Overview

SwaAdhyaya is a custom-built Learning Management System (LMS) developed using the MERN stack. It offers a comprehensive platform for both instructors and students to manage and access educational content efficiently. The application ensures secure access through user authentication and protected routes.


## Screenshots of the Features 

    https://drive.google.com/drive/folders/1k8Ep8aZI6exKr0AMhJBS8BMihuNE0nNF?usp=drive_link
    




## Features

### General Features

- User Authentication (Login/Signup)
- Secure access with protected routes
- Role-based access control (Instructor/Student)
- Integrated payment gateway (Stripe)

### Instructor Features

- Create and manage courses
- View revenue graphs
- Track course purchases
- Manage profile and settings

### Student Features

- Browse and purchase courses
- Track course progress
- View purchased courses
- Manage profile and settings

## Tech Stack

- **Frontend:** React, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Payment Gateway:** Stripe

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/swaadhyaya.git
2. Install dependencies for both client and server:
   ```bash
   cd swaadhyaya/client
   npm install
   cd ../server
   npm install
3. Create a .env file in the server directory and add your environment variables:
   ```bash
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_key
4.Run the application:
   ```bash
    npm start
