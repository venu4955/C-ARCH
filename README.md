# C-Arch

## Overview

C-Arch is a location-based professional services platform designed to connect **customers** with **civil engineers, architects, and construction-related professionals** required to build a house or commercial project. Instead of wasting weeks calling random contacts, users can discover verified professionals within a **100 km radius**, compare profiles, communicate directly, and book services — all in one app.

This is not a portfolio toy. C-Arch is built to solve a real coordination problem in the construction ecosystem.

---

## Problem Statement

The construction industry is fragmented:

* Customers struggle to find trustworthy professionals
* Professionals lack a centralized platform to showcase their work
* Communication and booking are inefficient and offline

C-Arch fixes this by acting as a **single digital marketplace** for construction services.

---

## Key Features

### 🔐 Authentication

* Email & Password login
* Google Sign-In
* Secure role-based access (Customer / Professional)

### 👤 Profile Management

* Separate profiles for:

  * Customers
  * Architects
  * Civil Engineers
* Professional profiles include:

  * Skills & services
  * Experience
  * Portfolio
  * Location & availability

### 📍 Location-Based Search

* Discover professionals within **100 km radius**
* Quick browsing of multiple profiles
* Filter and shortlist professionals easily

### 💬 Messaging System

* In-app real-time messaging
* Direct communication between customer and professional

### 📅 Booking System

* Service booking and scheduling
* Request-based workflow between customer and professional

---

## Tech Stack

### Frontend

* **Flutter** (Cross-platform mobile development)

### Backend

* **Node.js**
* **Express.js** (REST API)

### Database

* **MongoDB** (NoSQL, scalable)

### Other Tools

* JWT for authentication
* Google Maps API (location services)

---

## System Architecture

```
Flutter App
   │
   ├── REST API (Express.js)
   │        │
   │        └── MongoDB Database
   │
   └── Google Services (Auth & Maps)
```

---

## Installation & Setup

### Prerequisites

* Flutter SDK
* Node.js (v18+ recommended)
* MongoDB (local or cloud)

### Backend Setup

```bash
cd backend
npm install
npm start
```

### Frontend Setup

```bash
cd frontend
flutter pub get
flutter run
```

---

## Folder Structure (High-Level)

```
C-Arch/
├── frontend/        # Flutter application
├── backend/         # Node.js & Express API
├── models/          # MongoDB schemas
├── routes/          # API routes
├── controllers/     # Business logic
└── README.md
```

---

## Future Enhancements

* Payment gateway integration
* Rating & review system
* Admin dashboard
* AI-based professional recommendations
* Project tracking & milestones

---

## Target Users

* Homeowners & builders
* Civil engineers
* Architects
* Construction consultants

---

## Status

🚧 **Active Development**

Core features implemented. Optimization, UI polish, and scalability improvements are ongoing.

---

## Author

**Kanna**
B.Tech Final Year | App Developer

---

## License

This project is currently proprietary. Licensing will be defined in future releases.
