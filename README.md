# 🌐 ResQ-Bridge: Disaster Relief Assistance Platform (DRAP)

![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=for-the-badge)
![Stack](https://img.shields.io/badge/MERN-FullStack-blue?style=for-the-badge)
![Payment](https://img.shields.io/badge/Razorpay-Verified-orange?style=for-the-badge)

> *A centralized command center connecting Administrators, Volunteers, and the Public to streamline disaster response and resource allocation.*

---

## 👨‍💻 Why I Built This (The Context)

I am a **Computer Science undergraduate (B.Tech CSE)** at **CVR College of Engineering, Hyderabad**.

My journey began at **Little Flower High School (L.B. Nagar)** and **Narayana Junior College**, where I developed a deep fascination for systems architecture. Living in Hyderabad, I have witnessed how urban flooding disrupts communication channels. I realized that while volunteers are always ready to help, the **coordination gap** makes their efforts less effective.

### 💡 The Inspiration
This project was born during my preparation for the **JPMorgan Code for Good** initiative. I wanted to move beyond simple CRUD apps and build an **Enterprise-Grade System** that solves real logistical problems.

I spent **4 months** engineering this platform alongside my other research project, **[PharmaRec-Engine](https://github.com/sahilistrying/PharmaRec-Engine)**. While PharmaRec focused on algorithmic complexity (Medicine Recommendation), **ResQ-Bridge** was my deep dive into **Full-Stack Scalability**, real-time mapping, and secure financial integrations.

---

## 📸 Platform Gallery

### 🏠 Index Page (Live Operations)
Real-time shelter tracking and incident visualization using Google Maps API.
![Index Page](screenshots/dashboard-map.jpg)

### 💰 Donation & Fund Tracking
Transparent financial logging using Razorpay Integration.
![Donation View](screenshots/Donation.png)

### 🧑‍💼 Admin Control Panel
Centralized dashboard for verifying volunteers and allocating inventory.
![Admin View](screenshots/Admin.png)

---

## 🚀 Features

### 🧑‍💼 Admin (Command & Control)
* **Resource Logistics:** Allocate & monitor supplies (Food, Meds, Shelter capacity).
* **Task Dispatch:** Assign rescue missions to volunteers based on geo-location.
* **Financial Oversight:** Track incoming **Razorpay** donations and fund usage transparency.

### 🧑‍🚒 Volunteer (Ground Ops)
* **Skill-Based Registration:** Tag skills (Medical, Rescue, Driving).
* **Real-time Updates:** Accept missions and update status from the field.

### 👥 Public (Victims & Donors)
* **Incident Reporting:** Geo-tagged SOS alerts.
* **Shelter Locator:** Find nearest safe zones with live capacity status.
* **Donations:** Secure monetary or material contributions via **Razorpay**.

---

## 🧱 Tech Stack

| Layer | Technology | Usage |
| :--- | :--- | :--- |
| **Frontend** | React.js | Responsive UI, State Management |
| **Backend** | Node.js, Express.js | RESTful API Architecture |
| **Database** | MongoDB | Geo-spatial Data & User Records |
| **Payment** | Razorpay | PCI-Compliant Donation Gateway |
| **Maps** | Google Maps API | Shelter & Incident Visualization |

---

## 🔧 Setup & Installation

1. **Clone & Install**
   git clone https://github.com/sahilistrying/ResQ-Bridge.git
   npm install # (Run in both backend/ and frontend/ folders)

2. **Run the Ecosystem**
   npm start # (Run in both folders)

---
<p align='center'><i>Built by Sahil. Engineered for Impact.</i></p>
