# 🚗 Smart Carpool App

A smart carpool mobile application designed for students, using personalized ride matching powered by NLP and a BERT-based recommendation model.

---

## 📽️ Demo Video  
To get a quick glimpse of the system in action, watch our short demo on YouTube:
[🎬 YouTube – Smart Carpool App](https://www.youtube.com/watch?v=vE8tia67qhk)

Note:
This video showcases a small part of the full experience – specifically the ride-request flow.
Core features such as smart recommendations, real-time alerts, and full user interactions are implemented in the system but not fully shown in the video.

---

## 📂 Project Repositories

- 🔧 **.NET Web API (Backend):** [SmartCarpool-Backend](https://github.com/noampdut/Student-Riding-App-Server-Side-.git)
- 📱 **Android App (Client):** [Student-Riding-App (Frontend)](https://github.com/noampdut/Student-Riding-App-Android.git)

---


## 📱 Overview

SmartCarpool is a ride-sharing app tailored for students, aiming to connect the most compatible drivers and passengers through a combination of static ride data, semantic analysis, and external optimization APIs.

The project consists of an Android mobile app, a backend API in .NET, and a Python-based machine learning recommendation engine.

---

## 🧠 Recommendation Engine – How It Works

Our recommendation system blends two approaches to achieve optimal matching:

### 1. 🔢 Structured Matching – Hard Features
- **Inputs:** departure time, location, distance, availability, ride history, and user reviews
- **Processing:** Google Maps APIs for optimal route calculations
- **Goal:** filter matches based on logistical feasibility and preferences

### 2. 🧠 Semantic Matching – NLP & ML
- Each user writes a short free-text description (e.g., "I'm quiet and like chill music")
- A **BERT-based NLP model** processes bios from both drivers and passengers
- The model computes **semantic similarity** to determine psychological and behavioral compatibility
- Final match score = semantic score + structured data score

This combination allows the app to recommend not just any available ride, but rides that feel safer, smoother, and more pleasant.

---

## 🔧 Technologies Used

| Layer       | Stack                                      |
|-------------|--------------------------------------------|
| Frontend    | Android Studio (Java)                      |
| Backend     | ASP.NET Core Web API                       |
| ML/NLP      | Python + BERT for recommendation engine    |
| Database    | Firebase Authentication + MongoDB          |
| Realtime    | Firebase Notifications                     |
| Hosting     | Google Cloud Platform (GCP)                |

---

## 🧩 Key Features

- 🔐 Role-based user registration (drivers & passengers)
- 📍 Create, search, and manage ride requests and offers
- 📊 AI-based matching using BERT and structured ride data
- 🔔 Push notifications using Firebase
- ⭐ Ride rating system for both parties
- 🧱 Modular backend (.NET MVC + Services)


---

## ⚠️ Setup Notes

- The project is **not deployable out-of-the-box** due to reliance on paid services:
  - Google Cloud API (Maps, Places, Distance Matrix)
  - Firebase (Auth + Realtime Notifications)
  - MongoDB (key)

- To run locally:
  - Register your own API keys for each external service
  - Set up the backend with your connection strings
  - Train or load the pre-trained BERT model in the Python component

---

## 📌 Status

- Fully implemented logic and integrations
- UI is minimal and functional (not production-ready)
- Designed to demonstrate architecture and algorithmic strength

---

## 👤 Author

Created by Noam Pdut and Lilach Lacham –  
[GitHub Profile](https://github.com/noampdut)

---



