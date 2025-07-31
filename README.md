# sahayak_riverathon

### 🚨 Real-time flood alerts. Hyperlocal risk simulation. LiDAR + AI-powered evacuation support.

---

## 🧠 Overview

**FloodGuardAI** is a smart flood risk management platform designed to provide **personalized, terrain-aware alerts** and **evacuation planning** using **LiDAR DEM data**, **AI-based rainfall simulations**, and **infrastructure vulnerability mapping**.

Built as part of **Riverathon 1.0 – National River Hackathon**, this project aims to reduce flood-related casualties and property damage through predictive analytics and visual decision support tools.

---

## 🧩 Problem Statement

> Current flood warnings are generalized, lack precision, and fail to offer personalized evacuation strategies—leading to unnecessary loss of life and property.

---

## 🎯 Objectives

- Predict flood-prone areas using **AI models trained on LiDAR + rainfall data**
- Provide **real-time, location-specific flood risk visualizations**
- Offer **custom evacuation routes** and show **vulnerable infrastructure**
- Enable simulation of **user-defined rainfall scenarios**
- Assist **authorities and citizens** in better disaster planning

---

## 💡 Proposed Solution

### 🔧 Core Modules:
- **Rainfall-to-Risk Simulator**: AI-based flood impact simulation from rainfall input
- **Dynamic Risk Mapping**: Real-time flood map overlays using terrain + water flow
- **Personalized Emergency Alerts**: Smart notifications based on geolocation + elevation
- **Infrastructure Impact Estimator**: Lists at-risk schools, hospitals, roads
- **Evacuation & Shelter Routing**: Terrain-optimized safe path suggestion tool

---

## 👥 Target Users

| Group | Benefits |
|-------|----------|
| **Citizens in Flood Zones** | Personalized alerts, safe evacuation maps |
| **Disaster Authorities** | Real-time flood intel, infrastructure risk assessment |
| **Emergency Responders** | Live-risk data, better planning & faster response |

---

## 🛠️ Tech Stack

### 💻 Frontend:
- HTML, CSS, JS
- Google Maps JavaScript API
- Leaflet.js (for dynamic risk maps)

### 🔙 Backend:
- Python (Flask API)
- Node.js + Express (routing + data handling)

### 🧠 AI & ML:
- PyTorch / TensorFlow (flood impact models)
- HuggingFace Transformers (NLP-based future advisory support)
- NASA Earthdata + GEDI (LiDAR elevation data)
- OpenWeatherMap (rainfall data)

### 🗃️ Database:
- PostgreSQL / MongoDB
- AWS (for future scale/cloud storage)

### 📡 Communication (Mock for MVP):
- Twilio API (alerts via SMS/WhatsApp)
