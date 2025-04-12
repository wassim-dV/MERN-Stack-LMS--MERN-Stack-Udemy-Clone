# 🎓 MERN Stack LMS – Udemy Clone

An intelligent, full-stack e-learning platform built with the **MERN stack**, inspired by Udemy. This platform allows users to explore, enroll in, and interact with courses, with integrated AI features for personalized learning experiences.

## 🚀 Features

- 🔐 User Authentication with JWT (register/login)
- 📚 Course listing, filtering, and search
- 💬 Chatbot assistant powered by OpenAI (LLM)
- 🎯 Personalized course recommendations
- 📝 Admin panel to manage users and courses
- 🎥 Video lectures with course progress tracking
- 💳 Payment gateway integration (e.g. PayPal or Stripe)
- 📱 Responsive design for mobile and desktop

## 🧰 Tech Stack

### Front-end:
- React.js
- Redux or Context API
- React Router
- Tailwind CSS

### Back-end:
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- OpenAI API

## 📸 Screenshots

> *(Insert images or GIFs showcasing the UI, chatbot in action, or the course player.)*

## 🛠️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/MERN-Stack-LMS--MERN-Stack-Udemy-Clone.git
cd MERN-Stack-LMS--MERN-Stack-Udemy-Clone

2. Install dependencies
Front-end:

cd client
npm install
Back-end:


cd ../server
npm install
3. Environment Setup
Create a .env file in the server/ directory and add the following:

env

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
OPENAI_API_KEY=your_openai_api_key
4. Run the Application
Start the server:


cd server
npm run dev
Start the client:

cd client
npm start
Visit http://localhost:3000 to explore the app!

📁 Folder Structure

MERN-Stack-LMS--MERN-Stack-Udemy-Clone/
├── client/         # React Frontend
├── server/         # Express Backend
├── README.md
└── ...
