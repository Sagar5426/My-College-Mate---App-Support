<style>
  /* iOS Pro Dark Theme Overrides */
  :root {
    --bg-color: #000000;
    --text-primary: #f5f5f7;
    --text-secondary: #a1a1a6;
    --card-bg: #1c1c1e;
    --card-border: #38383a;
    --accent: #0a84ff;
  }

  body {
    background-color: var(--bg-color);
    color: var(--text-primary);
    font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    max-width: 800px;
    margin: 0 auto;
    padding: 40px 24px;
    -webkit-font-smoothing: antialiased;
  }

  h1, h2, h3 { 
    color: #ffffff; 
    font-weight: 700; 
    letter-spacing: -0.02em; 
  }
  
  h2 { 
    border-bottom: 1px solid var(--card-border); 
    padding-bottom: 12px; 
    margin-top: 56px; 
    font-size: 1.5rem;
  }
  
  a { 
    color: var(--accent); 
    text-decoration: none; 
    transition: opacity 0.2s ease; 
  }
  
  a:hover { opacity: 0.8; }
  
  blockquote { 
    border-left: 4px solid var(--accent); 
    background-color: var(--card-bg); 
    padding: 16px 20px; 
    margin: 24px 0; 
    border-radius: 0 12px 12px 0; 
    color: var(--text-secondary); 
    font-size: 0.95em;
  }

  hr { 
    border: 0; 
    height: 1px; 
    background: var(--card-border); 
    margin: 48px 0; 
  }

  /* Hero Section */
  .hero { text-align: center; margin-bottom: 48px; }
  .hero-title { font-size: 3rem; margin-bottom: 16px; background: linear-gradient(135deg, #ffffff, #a1a1a6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
  .hero-subtitle { font-size: 1.2rem; color: var(--text-secondary); font-weight: 500; margin-bottom: 8px; }
  .hero-desc { color: var(--text-secondary); font-size: 1rem; margin-bottom: 32px; }
  
  .badge-container { display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; margin-bottom: 32px; }
  .badge-container img { border-radius: 6px; }

  /* Premium Feature Cards */
  .feature-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 16px;
    margin: 24px 0;
  }

  @media (min-width: 600px) {
    .feature-grid { grid-template-columns: repeat(2, 1fr); }
  }

  .feature-card {
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    border-radius: 16px;
    padding: 24px;
    transition: transform 0.2s ease, background 0.2s ease;
  }

  .feature-card:hover {
    background: #242426;
    transform: translateY(-2px);
  }

  .feature-icon {
    font-size: 28px;
    margin-bottom: 16px;
    display: inline-block;
    background: #2c2c2e;
    width: 48px;
    height: 48px;
    line-height: 48px;
    text-align: center;
    border-radius: 12px;
  }

  .feature-title {
    font-size: 1.1rem;
    font-weight: 600;
    color: #ffffff;
    margin: 0 0 8px 0;
  }

  .feature-desc {
    margin: 0;
    color: var(--text-secondary);
    font-size: 0.95rem;
    line-height: 1.5;
  }

  /* Footer */
  .footer { 
    text-align: center; 
    margin-top: 80px; 
    color: var(--text-secondary); 
    font-size: 0.9em; 
  }
</style>

<div class="hero">
  <h1 class="hero-title">MyCollegeMate</h1>
  
  <div class="badge-container">
    <img src="https://img.shields.io/badge/Platform-iOS%2026.0%2B-0a84ff?style=flat-square&logo=apple&logoColor=white" alt="iOS Platform" />
    <img src="https://img.shields.io/badge/Swift-SwiftUI-f05138?style=flat-square&logo=swift&logoColor=white" alt="SwiftUI" />
    <img src="https://img.shields.io/badge/iCloud-Sync-34c759?style=flat-square&logo=icloud&logoColor=white" alt="iCloud" />
    <img src="https://img.shields.io/badge/Privacy-Privacy%20First-32d74b?style=flat-square" alt="Privacy First" />
  </div>

  <p class="hero-subtitle">The ultimate personal academic companion for iOS</p>
  <p class="hero-desc">Track attendance, scan timetables with AI, and organize course notes seamlessly.</p>

  <a href="https://apps.apple.com/in/app/mycollegemate-attendance/id6754844571">
    <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="52">
  </a>
</div>

## 🌟 Overview

**MyCollegeMate** is designed to streamline academic management for college students. By combining AI-powered timetable extraction, real-time Lock Screen & Dynamic Island widgets, and intelligent attendance metrics, MyCollegeMate ensures you never miss a lecture or fall behind on requirements.

> **Note on Data Security:** All core student data (subjects, schedules, and attendance logs) remains 100% private to your local device and your personal iCloud storage. 

## 🚀 Key Features

<div class="feature-grid">
  
  <div class="feature-card">
    <div class="feature-icon">🤖</div>
    <h3 class="feature-title">AI Timetable Scanner</h3>
    <p class="feature-desc">Snap a picture of your physical or digital schedule. Powered by Google's Gemini API, the app securely extracts course names, times, and venues in seconds.</p>
  </div>

  <div class="feature-card">
    <div class="feature-icon">🏝️</div>
    <h3 class="feature-title">Live Activities</h3>
    <p class="feature-desc">View your ongoing and upcoming classes at a glance directly from your Lock Screen or Dynamic Island without even opening the app.</p>
  </div>

  <div class="feature-card">
    <div class="feature-icon">📊</div>
    <h3 class="feature-title">Smart Attendance</h3>
    <p class="feature-desc">Monitor subject-wise percentages and automatically calculate how many classes you can safely skip or need to attend to hit your target goals.</p>
  </div>

  <div class="feature-card">
    <div class="feature-icon">📅</div>
    <h3 class="feature-title">Interactive Daily Logs</h3>
    <p class="feature-desc">Navigate an intuitive daily schedule to mark classes as attended, missed, or cancelled with a single tap.</p>
  </div>

  <div class="feature-card">
    <div class="feature-icon">🗂️</div>
    <h3 class="feature-title">Document Hub</h3>
    <p class="feature-desc">Store, organize, and view PDFs and lecture notes grouped by subject. Import directly via the iOS Share Sheet.</p>
  </div>

  <div class="feature-card">
    <div class="feature-icon">☁️</div>
    <h3 class="feature-title">iCloud Sync</h3>
    <p class="feature-desc">Seamless end-to-end synchronization across all your Apple devices via iCloud, alongside smart scheduled class notifications.</p>
  </div>

</div>

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
  <p>© 2026 Sagar Jangra. Made with ❤️ in Gurugram.</p>
</div>
