# 🛡️ RoadGuard — Crowd-Sourced Road Hazard Reporting

> **Report. Verify. Navigate Safely.**

A crowd-sourced platform that turns commuter reports into verified hazard hotspots, live heatmaps, and safer route recommendations for Coimbatore.

🌐 **Live Demo:** [https://ranjeth314-rgb.github.io/RoadGuard/](https://ranjeth314-rgb.github.io/RoadGuard/)

---

## 🏆 Smart Move Hackathon — KIT Coimbatore

**Team Spark** | SNS College of Technology

| Member | Role |
|--------|------|
| Haris M S | Developer |
| Logavinayaga V | Developer |
| Srihari V | Developer |
| Ranjeth P | Developer |

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 📍 **Real GPS Capture** | Auto-captures actual GPS coordinates with accuracy, altitude & speed |
| 📷 **Photo Evidence** | Camera, gallery or file upload with preview, filename & size display |
| 🗺️ **Live Heatmap** | Real-time hazard density visualization using Leaflet.js & OpenStreetMap |
| 💾 **Saved Reports** | Filter by type, delete, clear all, export CSV — persists in localStorage |
| 🏛️ **Civic Dashboard** | Live stats, animated bar chart, reports table, DBSCAN verification panel |
| 🛣️ **Safe Routing** | Smart route suggestions avoiding high-hazard zones |

---

## 🔬 How Verification Works — DBSCAN Algorithm

| Parameter | Value | Purpose |
|-----------|-------|---------|
| Radius (ε) | 500m | Cluster search radius |
| Min Reports | 3+ | Minimum independent reports needed |
| Time Window | 48h | Reports must be within 48 hours |

> A hazard hotspot is **confirmed** only after **3+ independent reports** within **500m radius** over **48 hours**, automatically filtering spam and false reports.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| Leaflet.js | Interactive maps |
| Geolocation API | Real GPS capture |
| LocalStorage | Data persistence |
| MediaDevices API | Camera access |
| OpenStreetMap | Map tiles |
| Leaflet.heat | Heatmap layer |

---

## 📊 Impact

- **1,247** reports filed
- **89** verified hazard zones
- **34** repairs initiated
- **12,000** safe routes served

---

## 🚀 Getting Started

1. Visit [https://ranjeth314-rgb.github.io/RoadGuard/](https://ranjeth314-rgb.github.io/RoadGuard/)
2. Allow location access when prompted
3. Tap **"Report a Hazard Now"** to submit your first report
4. Explore the **Heatmap**, **Safe Route**, and **Dashboard** pages

---

**Made with ❤️ by Team Spark 🔥**

