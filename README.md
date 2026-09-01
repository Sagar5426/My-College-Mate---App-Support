# 📘 MyCollegeMate

<div align="center">

 <img src="https://img.shields.io/badge/Platform-iOS%2026.0%2B-blue?style=for-the-badge&logo=apple" alt="iOS Platform" />
  <img src="https://img.shields.io/badge/Swift-SwiftUI-orange?style=for-the-badge&logo=swift" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/iCloud-Sync-cloud?style=for-the-badge&logo=icloud" alt="iCloud" />
  <img src="https://img.shields.io/badge/Privacy-Privacy%20First-brightgreen?style=for-the-badge" alt="Privacy First" />

  <br/><br/>

  **The ultimate personal academic companion for iOS**  
  *Track attendance, scan timetables with AI, and organize course notes seamlessly.*

  [**📲 Download on the App Store**](https://apps.apple.com/in/app/mycollegemate-attendance/id6754844571) 

</div>

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack & Architecture](#-tech-stack--architecture)
- [Privacy Policy](#-privacy-policy)
- [Support & Contact](#-support--contact)

---

## 🌟 Overview

**MyCollegeMate** is designed to streamline academic management for college students. By combining AI-powered timetable extraction, real-time Lock Screen & Dynamic Island widgets, and intelligent attendance metrics, MyCollegeMate ensures you never miss a lecture or fall behind on requirements.

> [!NOTE]
> All core student data (subjects, schedules, attendance logs) remains 100% private to your local device and personal iCloud storage.

---

## 🚀 Key Features

| Feature | Description |
| :--- | :--- |
| 🤖 **AI Timetable Scanner** | Snap a picture of your physical or digital schedule. Powered by Google's Gemini API, the app securely extracts course names, times, and venues to build your interactive weekly schedule in seconds. |
| 🏝️ **Live Activities & Dynamic Island** | View your ongoing and upcoming classes at a glance directly from your Lock Screen or Dynamic Island without opening the app. |
| 📊 **Smart Attendance Tracker** | Monitor subject-wise percentages and automatically calculate how many classes you can safely skip or need to attend to hit your target goals. |
| 📅 **Interactive Daily Logs** | Navigate an intuitive daily schedule to mark classes as attended, missed, or cancelled with ease. |
| 🗂️ **Document & Note Hub** | Store, organize, and view PDFs and lecture notes grouped by subject. Import directly via the iOS Share Sheet from messaging apps or file managers. |
| ☁️ **iCloud Sync & Reminders** | Seamless end-to-end synchronization across all your Apple devices via iCloud, alongside smart scheduled class notifications. |

---

## 🛠️ Tech Stack & Architecture

- **Language & UI:** Swift 5, SwiftUI
- **Widget Integration:** WidgetKit, ActivityKit (Live Activities & Dynamic Island)
- **AI Processing:** Google Gemini API (Ephemeral vision-to-text timetable parsing)
- **Data Syncing:** Apple CloudKit / iCloud Container
- **Analytics & Diagnostics:** Firebase Analytics & Crashlytics (Anonymous telemetry)

---

## 🔒 Privacy Policy

Your privacy is paramount. **MyCollegeMate** is built on privacy-by-design principles:

### 📱 Personal App Data
All core data—including subject lists, timetable schedules, notes, and attendance histories—is stored exclusively on your local device. If iCloud is enabled, data is synchronized via your private Apple iCloud container. **We do not collect, host, or have access to your personal academic records.**

### 🤖 AI Timetable Scanning
When utilizing the automated timetable scanner feature:
- Selected image files are transmitted securely over SSL to Google's Gemini API.
- Images are processed **ephemerally** in-memory solely for text identification and schedule structuring.
- Images are **never saved, archived, or linked to your identity**.

### 📊 Analytics & Diagnostics
To ensure stability and fix crashes:
- Anonymous metrics are collected via **Firebase Analytics** and **Crashlytics**.
- Information gathered includes device model, iOS version, app performance logs, and stack traces during crashes.
- This telemetry contains **zero personally identifiable information (PII)** and is strictly used to maintain and improve application performance.

---

## 💬 Support & Contact

Have questions, bug reports, or feature requests? We'd love to hear from you!

- 📧 **Email:** [sagarjangra880@gmail.com](mailto:sagarjangra880@gmail.com)
- ⏱️ **Response Time:** We aim to respond to all inquiries within **48 hours**.

---

<div align="center">

Made with ❤️ for students everywhere.

</div>
