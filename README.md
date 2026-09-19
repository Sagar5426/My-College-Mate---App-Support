<style>
  /* Premium Dark Theme Overrides */
  body {
    background-color: #09090b;
    color: #e2e8f0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.7;
    max-width: 800px;
    margin: 0 auto;
    padding: 40px 24px;
  }
  h1, h2, h3 { color: #f8fafc; font-weight: 600; tracking: tight; }
  h2 { border-bottom: 1px solid #27272a; padding-bottom: 10px; margin-top: 48px; }
  a { color: #3b82f6; text-decoration: none; transition: color 0.2s ease; }
  a:hover { color: #60a5fa; text-decoration: underline; }
  table { width: 100%; border-collapse: collapse; margin: 24px 0; background-color: #18181b; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1); }
  th, td { border: 1px solid #27272a; padding: 16px; text-align: left; }
  th { background-color: #27272a; color: #f8fafc; font-weight: 600; }
  blockquote { border-left: 4px solid #3b82f6; background-color: #18181b; padding: 16px 20px; margin: 0; border-radius: 0 8px 8px 0; color: #94a3b8; }
  hr { border: 0; height: 1px; background: #27272a; margin: 48px 0; }
  .badge-container { display: flex; gap: 8px; justify-content: center; flex-wrap: wrap; margin-bottom: 24px; }
  .footer { text-align: center; margin-top: 64px; color: #71717a; font-size: 0.9em; }
</style>

<div align="center">
  <h1>📘 MyCollegeMate</h1>
  
  <div class="badge-container">
    <img src="https://img.shields.io/badge/Platform-iOS%2017.0%2B-0a84ff?style=for-the-badge&logo=apple&logoColor=white" alt="iOS Platform" />
    <img src="https://img.shields.io/badge/Swift-SwiftUI-f05138?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI" />
    <img src="https://img.shields.io/badge/iCloud-Sync-34c759?style=for-the-badge&logo=icloud&logoColor=white" alt="iCloud" />
    <img src="https://img.shields.io/badge/Privacy-Privacy%20First-32d74b?style=for-the-badge" alt="Privacy First" />
  </div>

  <p><b>The ultimate personal academic companion for iOS</b></p>
  <p><i>Track attendance, scan timetables with AI, and organize course notes seamlessly.</i></p>
  <br/>

  <a href="https://apps.apple.com/in/app/mycollegemate-attendance/id6754844571">
    <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="50">
  </a>
</div>

## 🌟 Overview

**MyCollegeMate** is designed to streamline academic management for college students. By combining AI-powered timetable extraction, real-time Lock Screen & Dynamic Island widgets, and intelligent attendance metrics, MyCollegeMate ensures you never miss a lecture or fall behind on requirements.

> **Note on Data Security:** All core student data (subjects, schedules, and attendance logs) remains 100% private to your local device and your personal iCloud storage. 

## 🚀 Key Features

| Feature | Description |
| :--- | :--- |
| 🤖 **AI Timetable Scanner** | Snap a picture of your physical or digital schedule. Powered by Google's Gemini API, the app securely extracts course names, times, and venues to build your interactive weekly schedule in seconds. |
| 🏝️ **Live Activities** | View your ongoing and upcoming classes at a glance directly from your Lock Screen or Dynamic Island without opening the app. |
| 📊 **Smart Attendance Tracker** | Monitor subject-wise percentages and automatically calculate how many classes you can safely skip or need to attend to hit your target goals. |
| 📅 **Interactive Daily Logs** | Navigate an intuitive daily schedule to mark classes as attended, missed, or cancelled with a single tap. |
| 🗂️ **Document Hub** | Store, organize, and view PDFs and lecture notes grouped by subject. Import directly via the iOS Share Sheet from messaging apps or file managers. |
| ☁️ **iCloud Sync** | Seamless end-to-end synchronization across all your Apple devices via iCloud, alongside smart scheduled class notifications. |

## 🛠️ Tech Stack & Architecture

- **Language & UI:** Swift, SwiftUI, SwiftData
- **Widget Integration:** WidgetKit, ActivityKit (Live Activities & Dynamic Island)
- **AI Processing:** Google Gemini API (Ephemeral vision-to-text parsing)
- **Data Syncing:** Apple CloudKit / iCloud Container
- **Analytics:** Firebase Analytics & Crashlytics (Anonymous telemetry)

## 🔒 Privacy Policy

Your privacy is paramount. **MyCollegeMate** is built strictly on privacy-by-design principles:

### Personal App Data
All core data—including subject lists, timetable schedules, notes, and attendance histories—is stored exclusively on your local device. If iCloud is enabled, data is synchronized via your private Apple iCloud container. **We do not collect, host, or have access to your personal academic records.**

### AI Timetable Scanning
When utilizing the automated timetable scanner feature:
- Selected image files are transmitted securely over SSL to Google's Gemini API.
- Images are processed **ephemerally** in-memory solely for text identification and schedule structuring.
- Images are **never saved, archived, or linked to your identity**.

### Analytics & Diagnostics
To ensure stability and fix crashes:
- Anonymous metrics are collected via Firebase Analytics and Crashlytics.
- Information gathered includes device model, iOS version, app performance logs, and stack traces during crashes.
- This telemetry contains **zero personally identifiable information (PII)** and is strictly used to maintain and improve application performance.

## 💬 Support & Contact

Have questions, bug reports, or feature requests? Reach out anytime.

- 📧 **Email:** [sagarjangra880@gmail.com](mailto:sagarjangra880@gmail.com)
- ⏱️ **Response Time:** We aim to respond to all inquiries within 48 hours.

<div class="footer">
  <p>© 2026 Jangra Sagar. Made with ❤️ in Gurugram.</p>
</div>
