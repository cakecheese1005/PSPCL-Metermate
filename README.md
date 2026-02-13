# ⚡ PSPCL AI Meter Reading System (MVP)

An offline-first AI-powered mobile application for smart electricity meter reading, designed for real-world field conditions.

---

## 🚀 Project Overview

This system is built for PSPCL field officers to:

- Capture meter images
- Detect blurred images
- Extract meter readings using OCR
- Calculate electricity bills
- Work completely offline
- Automatically sync data when internet is available

The architecture is designed to be secure, scalable, and production-ready.

---

## 🧠 Key Features (MVP Scope)

### 📱 Mobile Application (Flutter)

- Login screen
- Dashboard with daily stats
- Meter reading capture screen (UI)
- Offline network detection
- Pending sync tracking
- Local-first workflow

### 🖥 Backend (FastAPI)

- Authentication APIs
- Meter reading APIs
- Sync endpoint (planned)
- PostgreSQL integration (planned)

### 🌐 Admin Dashboard (React – Planned)

- Review flagged readings
- View uploaded images
- Approve / reject entries
- Escalate to LCR team

---

## 🏗 Architecture Overview

<img width="350" height="387" alt="image" src="https://github.com/user-attachments/assets/5f068555-4cde-4fec-9b79-ff3891442fda" />


Mobile works independently without internet.
Server becomes authoritative when sync happens.

---

## 📂 Project Structure

<img width="539" height="294" alt="image" src="https://github.com/user-attachments/assets/064e061f-767d-4618-b88d-81e21b603bfc" />

---

## ⚙️ Tech Stack

### Mobile
- Flutter
- SQLite (offline storage)
- connectivity_plus
- Image capture (planned)
- OCR integration (team module)

### Backend
- FastAPI
- PostgreSQL
- SQLAlchemy
- JWT Authentication

### Admin Panel
- React
- Material UI

---

## 📶 Offline-First Design

The system ensures:

- Data capture without internet
- Local encrypted storage
- Pending sync queue
- Auto-sync when connection is restored
- Provisional billing until server validation

---

## 🔐 Security Measures

- JWT-based authentication
- HTTPS communication
- Role-based access control
- Local data protection
- Audit-ready architecture

---

## 🛠 Current Development Status

- [x] Project structure setup
- [x] GitHub repository initialized
- [x] Login UI (MVP)
- [x] Dashboard UI with network awareness
- [ ] Meter capture screen
- [ ] SQLite integration
- [ ] Sync service
- [ ] OCR integration
- [ ] Bill calculation module

---

## 👩‍💻 Contributors

- Mobile Development
- Backend Development
- AI / OCR Model Training
- Admin Dashboard

---

## 📌 Vision

To build a reliable, AI-powered, offline-capable smart meter reading system suitable for rural and urban India.

---

## 📄 License

This project is currently under development and not licensed for public distribution.


