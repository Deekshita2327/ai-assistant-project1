# SmartQuery – AI-Powered Q&A System

A full-stack AI-powered web application that allows users to ask questions and receive concise, structured responses using an AI model.

---

## 🌐 Live Demo

* Frontend: https://ai-assistant-project-gamma.vercel.app
* Backend: https://ai-assistant-project-m2dq.onrender.com

---

## 🚀 Features

* Ask questions through a simple and clean UI
* AI-generated responses in bullet-point format
* Full-stack integration (React + Node.js + MongoDB)
* API integration with Groq AI
* Error handling for API failures
* Deployed and accessible via public URLs

---

## 🛠️ Tech Stack

* Frontend: React (Vite), JavaScript, CSS
* Backend: Node.js, Express.js
* Database: MongoDB Atlas (Mongoose)
* AI API: Groq API
* Deployment: Vercel (Frontend), Render (Backend)

---

## 📂 Project Structure

* backend/ → Express server, API routes, AI service
* frontend/ → React UI application

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Deekshita2327/ai-assistant-project1.git
cd ai-assistant-project1
```

---

### 2. Install dependencies

```bash
cd backend
npm install

cd ../frontend
npm install
```

---

### 3. Environment Variables

Create a `.env` file inside the **backend** folder and add:

```env
GROQ_API_KEY=your_api_key
MONGO_URI=your_mongodb_connection_string
```

---

### 4. Run the project

#### Start Backend

```bash
cd backend
node server.js
```

#### Start Frontend

```bash
cd frontend
npm run dev
```

---

## 🧠 Description

SmartQuery is a full-stack conversational AI application designed to provide quick and structured answers to user queries. It integrates a React frontend with a Node.js backend, connects to MongoDB for database operations, and uses the Groq API to generate intelligent responses.

This project demonstrates real-world concepts such as API integration, environment variable management, full-stack communication, and deployment workflows.

---

## 📌 Notes

* Sensitive data (API keys, DB credentials) are stored securely using environment variables
* A clean repository is maintained following best practices
