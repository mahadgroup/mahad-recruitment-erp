# Mahad Recruitment ERP

> **Advanced recruitment ERP system for managing global manpower operations.**

---

## 🌍 Overview

Mahad Recruitment ERP is a comprehensive system designed to streamline international hiring operations. Built for recruitment agencies like Mahad Manpower, it automates the end-to-end hiring journey — from client job requests to final worker deployment.

---

## 🧩 Key Modules

- ✅ **Client Management**
- ✅ **Worker Profiles** (Asia & Africa-focused database)
- ✅ **Agency Coordination (India, Kenya, etc.)**
- ✅ **Interview Scheduling**
- ✅ **Selection Status Tracking** (Shortlisted, On-Hold, Deployed)
- ✅ **Video Resume Upload & AI Feedback**
- ✅ **Passport Scanning + Auto OCR**
- ✅ **Zoom Integration for Live Interview**
- ✅ **Twilio WhatsApp/SMS Notifications**
- ✅ **Analytics Dashboard + Reports**

---

## 🛠️ Tech Stack

- **Frontend:** Angular
- **Backend:** ASP.NET Core (C# API)
- **Database:** SQL Server
- **Authentication:** JWT / Role-based Auth
- **Cloud:** Plesk / Azure / VPS
- **APIs:** Zoom, Twilio, OCR AI

---

## 📁 Folder Structure (Suggested)

mahad-recruitment-erp/
├── frontend/ # Angular frontend UI
├── backend/ # ASP.NET Core API services
├── database/ # SQL schema, seed data
├── docs/ # Architecture, API references, flowcharts
├── assets/ # Logos, UI elements, visual guides
└── README.md

---

## 🚀 How to Run (Dev Mode)

### 🔧 Prerequisites
- Node.js / Angular CLI
- .NET 7 SDK
- SQL Server or Azure SQL
- Git, VS Code / Visual Studio

---

### 💻 Steps to Run

```bash
# Clone the project
git clone https://github.com/mahadgroup/mahad-recruitment-erp.git

# Frontend setup
cd frontend
npm install
ng serve

# Backend setup
cd backend
dotnet restore
dotnet run

# Database setup
Run schema from /database folder in SQL Server
