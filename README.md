# 🚨 SAHARA — Safety & Assistance Hub for Awareness, Response and Action

> **An emergency safety and assistance platform designed to connect users, hospitals, ambulance services, and emergency responders through a unified digital system.**
>
> 
## 🌐 Live Demo

🚀 **Try SAHARA Live:**

👉 https://sahara-ecru-chi.vercel.app/

[**🔗 Open SAHARA Live Demo**](https://sahara-ecru-chi.vercel.app/)

## 🌐 Project Overview

**SAHARA** is a web-based emergency assistance platform focused on providing quick access to safety and emergency services.

The platform helps users:

* 🚑 Request emergency ambulance assistance
* 📍 Find nearby hospitals
* 🗺️ View hospitals and emergency locations on maps
* 🚨 Access SOS emergency services
* 📡 Track ambulance availability and location
* 👤 Manage user and driver profiles
* 🏥 Support hospital and emergency-service management
* 💬 Access an emergency assistance chatbot
* 📞 Quickly access emergency contacts and services

The goal of SAHARA is to reduce the time required to find emergency assistance and improve communication between users, ambulance drivers, and hospitals.

---

## 🎯 Problem Statement

During an emergency, finding the nearest hospital or available ambulance can take valuable time.

Traditional emergency processes may involve:

* Searching manually for nearby hospitals
* Calling multiple emergency services
* Difficulty knowing ambulance availability
* Lack of centralized emergency information
* Limited visibility of ambulance locations

**SAHARA** addresses these challenges by bringing important emergency services together in one platform.

---

## 💡 Solution

SAHARA provides a centralized emergency assistance ecosystem where users can access emergency services through a simple web interface.

The system combines:

**User → Emergency Request → Ambulance → Hospital → Assistance**

This helps improve emergency coordination and provides users with faster access to relevant information.

---

## ✨ Key Features

### 🚨 Emergency & SOS

* One-click emergency assistance
* SOS emergency page
* Quick access to emergency services
* Emergency contact support

### 🚑 Ambulance Services

* Ambulance service request
* Ambulance availability
* Driver management
* Ambulance tracking interface
* Emergency request handling

### 📍 Nearby Hospitals

* Locate nearby hospitals
* Hospital information
* Map-based location
* Emergency facility discovery

### 🗺️ Location & Maps

* Map-based hospital discovery
* Location services
* Route and navigation support
* Location-based emergency assistance

### 💬 Emergency Chatbot

* Interactive emergency assistance interface
* Quick guidance for users
* Easy access from the platform

### 👤 User Management

* User registration
* Login
* Profile management
* Role-based pages

### 🏥 Hospital & Driver Management

* Hospital-related information
* Driver interface
* Ambulance management
* Emergency coordination

### 📱 Responsive Interface

The platform is designed to provide an accessible experience across different screen sizes.

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │       SAHARA        │
                    │ Emergency Platform  │
                    └──────────┬──────────┘
                               │
             ┌─────────────────┼─────────────────┐
             │                 │                 │
             ▼                 ▼                 ▼
        ┌─────────┐       ┌─────────┐       ┌─────────┐
        │  Users  │       │ Drivers │       │Hospitals│
        └────┬────┘       └────┬────┘       └────┬────┘
             │                 │                 │
             └─────────────────┼─────────────────┘
                               ▼
                    ┌─────────────────────┐
                    │   Backend / APIs    │
                    └──────────┬──────────┘
                               │
                    ┌──────────▼──────────┐
                    │      Database       │
                    └─────────────────────┘
```

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Responsive CSS
* jQuery

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB
* MongoDB-compatible backend configuration

### Python

* Python
* Flask-based application components

### APIs & Services

* Google Maps / location-related APIs
* Geolocation
* Mapping and navigation services
* Firebase integration

### Development Tools

* Visual Studio Code
* Git
* GitHub
* npm
* Live Server

---

## 📂 Project Structure

```text
SAHARA/
│
├── Backend/
│   ├── Controllers/
│   ├── Models/
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
│
├── images/
│   └── Project images and assets
│
├── src/
│   └── css/
│       ├── common.css
│       ├── driver.css
│       ├── hospital.css
│       ├── index.css
│       ├── login.css
│       ├── main.css
│       └── ...
│
├── scratch/
│
├── app.py
├── Firebase.js
├── index.html
├── login.html
├── signup.html
├── hospital.html
├── driver.html
├── chatbot.html
├── nearby.html
├── map.html
├── SOS.html
├── profile.html
├── volunteer-portal.html
├── wearable.html
├── script.js
├── scripts.js
├── style.css
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/nanmozhi-25/sahara-safety-ecosystem.git
```

### 2. Open the project

```bash
cd sahara-safety-ecosystem
```

### 3. Install backend dependencies

```bash
cd Backend
npm install
```

### 4. Configure the database

Create/configure your MongoDB connection and add the required connection details to the backend configuration.

### 5. Start the backend

```bash
node server.js
```

### 6. Run the frontend

Open the project in Visual Studio Code and launch the required HTML page using **Live Server**.

---

## 🔄 Emergency Workflow

```text
User opens SAHARA
        ↓
Emergency / SOS
        ↓
Request assistance
        ↓
Find available ambulance
        ↓
Ambulance / Driver coordination
        ↓
Locate nearest hospital
        ↓
Navigate to hospital
        ↓
Emergency assistance
```

---

## 🔐 Security

The project includes security-related configuration and documentation.

For production deployment:

* Keep API keys private
* Use environment variables
* Secure database credentials
* Enable HTTPS
* Implement authentication and authorization
* Validate user input
* Protect backend APIs

**Never commit API keys, passwords, database credentials, or private tokens to GitHub.**

---

## 🚀 Future Enhancements

* 🤖 AI-powered emergency assistance
* 📡 Advanced real-time ambulance GPS tracking
* 🔔 Push notifications
* 📱 Dedicated Android/iOS application
* 🧠 AI-based emergency classification
* 🏥 Live hospital bed availability
* 🚦 Advanced traffic-aware ambulance routing
* 💬 Real-time communication between users, drivers and hospitals
* 📊 Emergency analytics dashboard
* ☁️ Cloud deployment and scalable infrastructure

---

## 🎓 Project Purpose

SAHARA was developed as a technology project focused on applying web development, backend services, location-based services, and emergency-management concepts to a real-world safety problem.

---


## 📌 Repository

**GitHub:**
https://github.com/nanmozhi-25/sahara-safety-ecosystem

---

## 📄 License

This project is available under the **MIT License**.

---

### ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.
