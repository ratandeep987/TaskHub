# 🚀 TaskHub

TaskHub is a full-stack task management platform with an AI-powered Product Photography Studio. It helps users manage tasks efficiently while leveraging AI to generate professional product images from simple inputs.

## ✨ Features

### 🔐 Authentication

* Google OAuth Login
* GitHub OAuth Login
* Secure User Authentication with Supabase

### 📋 Task Management

* Create Tasks
* Edit Tasks
* Delete Tasks
* Mark Tasks as Completed
* User-specific Task Dashboard

### 🤖 AI Product Studio

* Generate AI Product Images
* Product Photography Enhancement
* AI-Powered Image Creation Workflow

### 👤 User Dashboard

* Personalized Dashboard
* Profile Management
* Activity Overview

## 🏗️ Architecture

```text
Frontend (Next.js + TypeScript)
        │
        ▼
Supabase Authentication & Database
        │
        ▼
Backend API (Flask)
        │
        ▼
AI Image Generation Service
```

## 🛠️ Tech Stack

### Frontend

* Next.js
* TypeScript
* React
* Tailwind CSS

### Backend

* Flask
* Python

### Database & Auth

* Supabase
* PostgreSQL

### AI

* AI Image Generation APIs

### Version Control

* Git
* GitHub

## 📂 Project Structure

```text
TaskHub/
│
├── backend/
│   └── app.py
│
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   ├── lib/
│   │   ├── providers/
│   │   └── types/
│   │
│   ├── public/
│   ├── package.json
│   └── .env.local
│
└── README.md
```

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/ratandeep987/TaskHub.git
cd TaskHub
```

### 2. Frontend Setup

```bash
cd frontend
npm install
```

Create `.env.local`

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
NEXT_PUBLIC_API_URL=http://localhost:5000/api
```

Start Frontend:

```bash
npm run dev
```

### 3. Backend Setup

```bash
cd backend
pip install -r requirements.txt
python app.py
```

## 🔑 Environment Variables

### Frontend

```env
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
NEXT_PUBLIC_API_URL=
```

### Backend

```env
AI_API_KEY=
SUPABASE_SERVICE_ROLE_KEY=
```

## 🎯 Roadmap

* [x] Project Architecture
* [x] Frontend Setup
* [x] Backend Setup
* [ ] Google OAuth Integration
* [ ] GitHub OAuth Integration
* [ ] Task CRUD Operations
* [ ] Dashboard Analytics
* [ ] AI Product Image Generation
* [ ] Image History
* [ ] Deployment

## 📸 Screenshots

Add screenshots as development progresses.

### Login Page

```
Coming Soon
```

### Dashboard

```
Coming Soon
```

### AI Studio

```
Coming Soon
```

## 👨‍💻 Developer

**Ratan Deep**

B.Tech CSIT (2023–2027)

Skills:

* Java
* Python
* JavaScript
* React
* Next.js
* Flask
* Supabase

GitHub: https://github.com/ratandeep987

## ⭐ Star the Repository

If you found this project interesting, consider giving it a star.
