<div align="center">

# 🎓 Smart College ERP System (Nexus)

### AI-Powered Enterprise Resource Planning Solution for Educational Institutions

[![React](https://img.shields.io/badge/React-18.x-blue?style=for-the-badge&logo=react)](https://react.dev/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Framework-009688?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![Supabase](https://img.shields.io/badge/Supabase-Database-3ECF8E?style=for-the-badge&logo=supabase)](https://supabase.com/)
[![Tailwind](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)

[Live Demo](#) • [Report Bug](#) • [Request Feature](#)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [Installation](#-installation)
- [Screenshots](#-screenshots)
- [Roadmap](#-roadmap)

---

## 🎯 About

**Nexus College ERP** is a next-generation Enterprise Resource Planning system designed specifically for modern educational institutions. Built with a decoupled architecture using a **Python FastAPI** backend and a **React.js** frontend, this platform seamlessly integrates Artificial Intelligence to automate tedious administrative workflows.

### ✨ Why Choose Nexus?

- 🚀 **Lightning Fast** - Built with FastAPI and Vite for incredible performance.
- 🤖 **AI-Powered** - Features automated timetable generation and NLP-based question paper analysis.
- 📊 **Real-time Sync** - Live database syncing using Supabase PostgreSQL.
- 🎨 **Glassmorphism UI** - Stunning, responsive dark-mode design built with Tailwind CSS.
- 👥 **Role-Based Access** - Distinct interfaces for Students, Teachers, and Admins.

---

## 🚀 Features

### 👨‍💼 AI & Automation

<details>
<summary>Click to expand AI features</summary>

- 🧠 **AI Question Paper Analyzer** - Upload PDFs of past exams; the system uses Scikit-Learn (TF-IDF) to analyze and predict topic weightage.
- 📅 **AI Timetable Generator** - Uses Google OR-Tools constraint programming to automatically generate conflict-free schedules.
- 📄 **1-Click Result Sheets** - Automatically generates PDF and Excel grade reports using `ReportLab` and `openpyxl`.

</details>

### 👨‍🏫 Academic Management

<details>
<summary>Click to expand Management features</summary>

- 📈 **Dynamic Dashboard** - Real-time overview of CGPA, attendance, and upcoming deadlines.
- ✅ **Attendance Tracking** - Live syncing attendance with automatic <75% red-alert warnings.
- 📚 **Assignment Portal** - Track submissions, deadlines, and graded status.
- 🎯 **Marks & Results** - Internal and external marks entry with automatic percentage calculation.

</details>

---

## 🛠️ Technology Stack

| Category | Technologies |
|----------|-------------|
| **Backend** | Python 3.10+, FastAPI, Uvicorn |
| **Frontend** | React.js (Vite), Tailwind CSS 4, Lucide React |
| **Database** | Supabase (PostgreSQL) |
| **AI / ML** | Scikit-Learn, NLTK, Google OR-Tools |
| **Data Export** | ReportLab (PDF), OpenPyXL (Excel), PyPDF2 |

---

## 📥 Installation

### Prerequisites

Ensure you have the following installed:

- ✅ [Node.js](https://nodejs.org/) (v18+)
- ✅ [Python](https://www.python.org/downloads/) (3.10+)
- ✅ A [Supabase](https://supabase.com/) account

### Step-by-Step Setup

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Nexus-ERP.git
cd Nexus-ERP
```

#### 2️⃣ Backend Setup (FastAPI)

Open a terminal and navigate to the backend:

```bash
cd backend
python -m venv venv
# Activate the environment:
# Windows: venv\Scripts\activate
# Mac/Linux: source venv/bin/activate

pip install -r requirements.txt
```

Create a `.env` file in the `backend/` folder and add your Supabase keys:
```env
SUPABASE_URL="https://your-project.supabase.co"
SUPABASE_KEY="your-anon-key"
```

Start the API:
```bash
python run.py
```
*(Runs on localhost:8001)*

#### 3️⃣ Frontend Setup (React)

Open a second terminal and navigate to the frontend:

```bash
cd frontend
npm install
npm run dev
```
*(Runs on localhost:5173)*

#### 4️⃣ Database Initialization
Run the provided SQL scripts in your Supabase SQL Editor to instantly generate the tables, schemas, and Row Level Security policies.

🎉 **Success!** Visit `http://localhost:5173` in your browser.

---

## 📸 Screenshots

*(Add your actual screenshots to a `Showcase/` folder and link them here)*
![Dashboard Demo](Showcase/dashboard.png)
![AI Analyzer](Showcase/ai_analyzer.png)

---

## 🗺️ Roadmap

### ✅ Completed Features
- [x] Modern Glassmorphism UI
- [x] FastAPI & Supabase Integration
- [x] Real-time Attendance & Marks Tracking
- [x] AI NLP Analyzer & Timetable Solver
- [x] Login Role-Based Authorization

### 🔜 Upcoming Features
- [ ] Authentication via Supabase Auth (JWT)
- [ ] Fee Payment Gateway Integration
- [ ] Parent Portal
- [ ] Library Management Module

---

<div align="center">

**Made with ❤️ by the Nexus Team**

*If this project helped you, consider giving it a star! ⭐*

</div>
