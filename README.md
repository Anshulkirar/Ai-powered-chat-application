# AI Chatbot Application 🤖✨

A full stack AI chatbot application built using **React**, **Node.js**, and **Express**, integrated with AI-powered text and image generation, credit-based usage, and online payments. The project is deployed on **Vercel** and demonstrates modern full-stack development best practices.


## 📌 Project Overview

This project is a complete **AI chatbot platform** where users can chat with AI, generate text and images, publish AI-generated images to a community gallery, and manage usage through a credit-based system.  
Users can purchase additional credits via **Stripe** payments, making the application monetization-ready.


## 🚀 Features

### 🔐 User Authentication
- User registration and login
- Encrypted passwords using **bcrypt**
- JWT-based authentication
- Secure user data handling

### 💬 Chat Functionality
- Create, view, search, and delete chats
- Sidebar with chat history and timestamps
- AI-generated responses for text and images
- Markdown support with syntax highlighting
- Auto-scroll and loading animations

### 🧠 AI Integration
- **Text Generation:** Google Gemini API (via OpenAI package)
- **Image Generation:** ImageKit AI
- Optimized image storage and transformations

### 🌍 Community Images
- Publish AI-generated images
- Public community gallery visible to all users

### 💳 Credit System
- 20 free credits for new users
- Text generation: **1 credit**
- Image generation: **2 credits**
- Purchase additional credits via Stripe

### 🎨 UI & UX
- Light/Dark mode toggle
- Fully responsive layout
- Mobile-friendly sidebar navigation
- Modern UI built with Tailwind CSS


## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router DOM
- React Context API
- Axios
- React Markdown
- Prism.js
- React Hot Toast

### Backend
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT Authentication
- bcryptjs
- Stripe API
- Svix (Stripe Webhooks)

### AI & Media
- Google Gemini API
- ImageKit

### Deployment
- Vercel (Frontend & Backend)


## 🔒 Security Highlights
- Password hashing with bcrypt
- JWT-based stateless authentication
- Secure Stripe webhook verification
- Environment variable protection


## 📦 Deployment

- Frontend deployed on **Vercel**
- Backend deployed on **Vercel**
- MongoDB hosted on **MongoDB Atlas**
- Secure environment variables configuration


## 📈 Key Learnings
- Full-stack application architecture
- AI API integration (text & image)
- Credit-based monetization system
- Stripe payment and webhook handling
- State management with React Context API
- Responsive UI with Tailwind CSS
- Production-ready deployment


## 🏁 Conclusion

This project demonstrates how to build a **scalable, secure, and monetized AI chatbot** using modern full-stack technologies. It covers everything from authentication and AI integration to payments, deployment, and responsive UI design.


⭐ If you find this project useful, consider giving it a star!
