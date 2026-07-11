<h1 align="center">🚀 AI Interview Preparation Platform</h1>

<p align="center">
An AI-powered MERN Stack application that analyzes resumes and job descriptions to generate a personalized interview preparation strategy using Google's Gemini API.
</p>

<p align="center">

![React](https://img.shields.io/badge/React-19-blue?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Express-green?logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-darkgreen?logo=mongodb)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)
![Gemini](https://img.shields.io/badge/AI-Gemini_API-blueviolet)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

</p>

---

## 🔗 Live Demo

**Frontend:** https://ai-interview-prep-platform-six.vercel.app

Click here: https://ai-interview-prep-platform-six.vercel.app

---

# 📖 Overview

Preparing for interviews requires understanding both the job requirements and your own strengths. This platform simplifies the process by using AI to analyze a candidate's resume and compare it with the target job description.

Based on this analysis, the application generates a personalized interview preparation plan that includes technical questions, behavioral questions, skill gap analysis, a compatibility score, and a structured learning roadmap.

---

# ✨ Features

### 🔐 Authentication

- Secure User Registration
- User Login
- JWT Authentication
- Protected Routes
- Token Blacklisting for Secure Logout

---

### 🤖 AI-Powered Analysis

- Upload Resume (PDF/DOCX)
- Self Description Support
- Job Description Analysis
- Resume Skill Extraction
- Candidate Skill Analysis

---

### 💼 Interview Preparation

Generate a personalized interview strategy consisting of:

- 📌 Technical Interview Questions
- 💬 Behavioral Interview Questions
- 🧠 AI-Generated Model Answers
- 🎯 Resume Match Score
- 📈 Skill Gap Analysis
- 🗺️ Personalized Preparation Roadmap

---

### 📂 Dashboard

- View Previous Interview Plans
- Review Match Scores
- Analyze Skill Gaps
- Access Generated Interview Questions
- Explore Personalized Learning Roadmaps

---

# 🛠️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| Frontend | React.js, CSS, React Router |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Authentication | JWT, Cookie Parser |
| AI | Google Gemini API |

---

# 🏗️ System Architecture

```
                Resume
                   │
                   ▼
         Resume Skill Extraction
                   │
                   ▼
Job Description ─────────────► Gemini API
                                   │
                                   ▼
                  Interview Strategy Generation
                                   │
       ┌──────────────┬──────────────┬──────────────┐
       ▼              ▼              ▼
Technical      Behavioral      Skill Gap
Questions       Questions       Analysis
       │              │              │
       └──────────────┴──────────────┘
                      ▼
               Match Score
                      ▼
            Preparation Roadmap
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/AI-Interview-Prep-Platform.git
```

---

## Backend

```bash
cd Backend
npm install
npm start
```

---

## Frontend

```bash
cd Frontend
npm install
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file inside the Backend folder.

```env

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

GEMINI_API_KEY=your_gemini_api_key
```

---

# 🚀 Workflow

```text
User Login
      │
      ▼
Upload Resume / Self Description
      │
      ▼
Paste Job Description
      │
      ▼
Gemini AI Analysis
      │
      ▼
───────────────────────────────────────────
✔ Resume Skill Extraction
✔ Job Requirement Analysis
✔ Resume Match Score
✔ Skill Gap Detection
✔ Technical Questions
✔ Behavioral Questions
✔ Model Answers
✔ Preparation Roadmap
───────────────────────────────────────────
      │
      ▼
Save Interview Plan
```

# 🌟 Current Capabilities

✅ Resume Analysis

✅ Job Description Analysis

✅ AI Interview Strategy

✅ Match Score Calculation

✅ Skill Gap Detection

✅ Personalized Preparation Roadmap

✅ Technical Interview Questions

✅ Behavioral Interview Questions

✅ Model Answers

✅ Authentication & Authorization

---

# 🚀 Future Enhancements

- 📄 Resume PDF Download
- 🤖 AI Resume Builder
- 📝 Cover Letter Generator
- 💬 AI Interview Chat Assistant
- 📈 Progress Analytics Dashboard
- 🏢 Company-Specific Interview Sets
- 🌙 Dark/Light Theme Toggle

---

# 📁 Project Structure

```
AI-Interview-Prep-Platform
│
├── Backend
│   ├── config
│   ├── controllers
│   ├── middlewares
│   ├── models
│   ├── routes
│   ├── services
│   └── server.js
│
├── Frontend
│   ├── src
│   ├── components
│   ├── features
│   ├── pages
│   └── assets
│
└── README.md
```

---

# 👨‍💻 Author

**Peeyush**

⭐ If you found this project helpful, consider giving it a star!
