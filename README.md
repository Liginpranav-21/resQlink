#  ResQLink

### **Connecting Help When Networks Fail**

An AI-powered emergency rescue ecosystem designed to assist people during disasters, accidents, and life-threatening situations — even in partially offline environments.

---

##  Project Overview

**ResQLink** is a **Final Year Engineering Project** focused on building an intelligent emergency response ecosystem that connects victims, rescue teams, hospitals, and administrators through real-time communication, AI assistance, GPS tracking, BLE emergency broadcasting, and smart emergency monitoring.

The system is designed to work in **remote areas**, **low-network conditions**, and **disaster situations**, ensuring emergency support remains accessible when traditional communication fails.

---

##  Problem Statement

During emergencies such as:

* Snake bites
* Animal attacks
* Landslides
* Floods
* Fires
* Earthquakes
* Heavy bleeding
* Fractures
* Heart attacks
* Forest emergencies
* Lost person situations
* Trekking accidents

victims often experience:

* Delayed rescue response
* No internet access
* Lack of first aid guidance
* Difficulty sharing exact location
* Poor emergency coordination

**ResQLink solves these problems using AI, GPS, Bluetooth, Firebase, and real-time monitoring systems.**

---

#  System Architecture

ResQLink consists of **three major systems**:

### 1️⃣ Mobile Application (User Side)

Victim-side emergency mobile application.

### 2️⃣ Desktop Admin Dashboard

Professional rescue command center for emergency monitoring.

### 3️⃣ Firebase Backend

Handles authentication, database, notifications, storage, and synchronization.

---

# 📱 Mobile Application Features

##  Authentication

* Email & Password Login
* Phone OTP Login
* Forgot Password
* Session Persistence
* Secure Authentication

---

##  Smart SOS System

### Emergency Levels

### Level 1 — Minor Emergency

* Notify emergency contacts

### Level 2 — Medical Emergency

* Notify nearby rescue teams

### Level 3 — Critical Emergency

* Send emergency to admin dashboard
* Trigger BLE emergency signal
* Start continuous GPS tracking
* Launch drone simulation support

### SOS Actions

* Share GPS coordinates
* Send emergency type
* Push notifications
* Emergency severity detection
* Rescue team alerts

---

##  Live GPS Tracking

* Real-time location tracking
* Latitude & Longitude
* Accuracy tracking
* Altitude detection
* Background GPS updates
* Nearby rescue center discovery

### Nearby Services

* Hospitals
* Police Stations
* Fire Stations
* Rescue Camps
* Emergency Shelters

---

##  Medical Profile

User emergency medical profile including:

### Personal Information

* Name
* Age
* Gender
* Height
* Weight
* Blood Group

### Medical Information

* Allergies
* Medications
* Medical Conditions
* Organ Donor Status

### Emergency Contacts

* Father
* Mother
* Guardian
* Friend

---

##  ResQAI Assistant

AI-powered emergency assistant.

### Features

* Emergency diagnosis
* Voice assistance
* Chat support
* Offline emergency guidance
* Survival recommendations

### Supported Languages

* English
* Tamil
* Hindi

### Example Prompts

> "I got snake bite"

> "I am bleeding heavily"

> "I cannot breathe properly"

---

## 🛰️ BlueBeacon BLE System

Offline emergency communication system using **Bluetooth Low Energy (BLE)**.

### Broadcast Data

* User ID
* GPS Coordinates
* Emergency Type
* Blood Group
* Battery Percentage
* Timestamp

### Nearby Detection

* Rescue Teams
* Volunteers
* Nearby ResQLink Users
* Drone Units

---

##  ResQDrone-X (Simulation)

Emergency rescue drone simulation system.

### Drone Features

* Victim tracking
* Thermal search simulation
* Search light simulation
* Medicine delivery simulation
* First aid kit support
* Live route tracking

### Drone Status

* Searching
* En Route
* Victim Found
* Rescue Completed

---

##  Emergency Categories

Supported emergencies include:

* Snake Bite
* Animal Attack
* Landslide
* Fire Accident
* Flood
* Earthquake
* Heavy Bleeding
* Fracture
* Heart Attack
* Lost in Forest
* Breathing Problems

Each emergency includes:

* Severity level
* First aid guide
* AI recommendation
* SOS trigger support

---

#  Desktop Admin Dashboard

Professional emergency command center dashboard.

## Features

* Real-time emergency monitoring
* Live victim tracking
* Rescue team management
* Drone control center
* Analytics dashboard
* Hospital monitoring
* Incident reporting

---

## Dashboard Widgets

* Active Emergencies
* Drones Online
* Rescue Teams Available
* Hospitals Available
* Average Response Time

---

## Live Emergency Monitoring

### Table Data

* Victim Name
* Emergency Type
* Severity
* GPS Location
* Status
* Assigned Team
* ETA

### Actions

* Dispatch Rescue Team
* Launch Drone
* Contact Victim

---

## Analytics Dashboard

### Charts & Reports

* Monthly emergency incidents
* Most dangerous zones
* Rescue success rate
* Daily incidents
* Average rescue time

---

# ⚙️ Tech Stack

## Frontend

* React
* TypeScript
* Tailwind CSS
* ShadCN UI

## Mobile

* React Native

## Backend

* Firebase

## Database

* Firebase Firestore

## Offline Storage

* SQLite
* IndexedDB
* AsyncStorage

## Authentication

* Firebase Authentication

## State Management

* Zustand

## Maps

* Google Maps API

## Notifications

* Firebase Cloud Messaging (FCM)

## Bluetooth

* BLE (Bluetooth Low Energy)

## AI

* Gemini API / OpenAI API

## Charts

* Recharts

## Deployment

* Vercel
* Firebase Hosting

## Version Control

* GitHub

---

#  Project Folder Structure

```txt
ResQLink/
│
├── frontend/
│
├── mobile-app/
│   ├── src/
│   │   ├── components/
│   │   ├── screens/
│   │   ├── navigation/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── store/
│   │   ├── firebase/
│   │   ├── types/
│   │   ├── utils/
│   │   └── assets/
│
├── admin-dashboard/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── dashboard/
│   │   ├── charts/
│   │   ├── maps/
│   │   ├── tables/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── store/
│   │   ├── firebase/
│   │   ├── types/
│   │   └── utils/
│
├── backend/
│   └── firebase/
│
├── shared/
│   ├── types/
│   ├── constants/
│   └── utils/
│
├── docs/
│
└── assets/
```

---

#  Firebase Collections

```txt
users
emergencies
medical_profiles
rescue_teams
hospitals
drone_logs
bluetooth_signals
incident_history
analytics
```

### User Roles

* User
* Rescue Team
* Admin

---

#  Offline Functionality

ResQLink supports **partial offline functionality**.

### Works Offline

✅ GPS Tracking
✅ Cached Maps
✅ Medical Profile Access
✅ Emergency History
✅ First Aid Database
✅ Bluetooth Emergency Broadcasting

### Auto Sync

When internet reconnects:

```txt
Local Storage → Firebase Sync
```

---

#  Security Features

* Firebase Security Rules
* Protected Routes
* Input Validation
* Rate Limiting
* Data Sanitization
* Role-Based Access

---

#  Testing Strategy

### Unit Testing

Individual component testing.

### Integration Testing

Service & Firebase connection testing.

### Component Testing

UI interaction testing.

### Edge Cases Covered

* No internet
* GPS denied
* Firebase failure
* Bluetooth disabled
* API failure
* Invalid inputs

---

#  Deployment

### Frontend

Deploy on **Vercel**

### Backend

Deploy using **Firebase Hosting**

---

#  Academic Purpose

This project is developed as a **Final Year Engineering Project** to demonstrate:

* Full Stack Development
* Mobile Application Development
* Firebase Integration
* Offline-first Systems
* AI Integration
* Real-time GPS Tracking
* BLE Communication
* Emergency Monitoring Architecture

---

#  Development Approach

The project follows a **Phase-by-Phase Development Model**:

1. Project Initialization
2. Firebase Backend Setup
3. Authentication System
4. Medical Profile
5. GPS Tracking
6. SOS System
7. Emergency Identification
8. Admin Dashboard
9. AI Assistant
10. Bluetooth Demo
11. Drone Simulation
12. Testing & Deployment

---

#  License

This project is developed for **educational and research purposes**.

---

##  ResQLink

**Saving Lives Through Smart Emergency Technology**
