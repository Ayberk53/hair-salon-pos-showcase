# 💈 SalonFlow POS — Local Desktop Salon & Cash Register Management System

> **Commercial Product (Closed Source)**  
> *This repository serves as a public showcase detailing the system architecture, core features, and user interface of SalonFlow POS. The source code is kept private due to commercial licensing; live demos and architectural walkthroughs are available upon request during technical interviews.*

---

## 📌 Overview
**SalonFlow POS** is a **portable Windows desktop Point-of-Sale (POS) and client management application** engineered for hair salons and beauty studios. Built with an **offline-first** approach, it eliminates recurring cloud subscription fees and internet dependency while ensuring high-speed local execution and data privacy.

---

## ✨ Key Features

* **👥 Client History & Walk-In Mode:** Tracks over 1+ year of service history per client, alongside a one-click **"Walk-In Client" (Salon Müşterisi)** mode for fast, anonymous checkouts.
* **💇‍♂️ Staff Commission & Performance Tracking:** Assigns services to individual stylists/staff members and automatically calculates daily, monthly, and annual revenue and commission breakdowns.
* **💳 Flexible Payment & Dynamic Pricing Engine:** 
  * Supports Cash, Credit Card (Visa), and single-transaction **Split Payments** (Cash + Card).
  * Real-time manual price overrides (custom discounts) and variable price entry for range-based services.
  * Instant service search and category filtering.
* **📊 Financial Analytics & Expense Tracking:** Comprehensive daily, monthly, and yearly turnover reports paired with lightweight operational expense logging *(e.g., supplies, utilities, market)* to track net profit.
* **⚙️ Multi-Salon Configurability:** Built-in admin panel allowing business owners to dynamically add/remove staff and update service price lists directly from the UI without code modifications.

---

## 🛠️ Tech Stack & Architectural Highlights

* **Desktop Runtime:** Standalone Windows x64 Portable Executable (zero-installation deployment, backward-compatible with legacy Windows versions and low-spec salon hardware).
* **Frontend Architecture:** Component-based UI optimized for low-latency search and rapid mouse/touch POS workflows.
* **Data & Persistence Layer:** Local relational database architecture with isolated user-directory storage, ensuring zero data loss when upgrading the application executable to newer versions.

---

## 📸 Screenshots

| POS & Fast Checkout | Staff Earnings & Commissions |
| :---: | :---: |
| ![POS Screen](screenshots/pos-screen.png) | ![Staff Report](screenshots/staff-report.png) |

| Financial & Expense Analytics | Service & Price Management |
| :---: | :---: |
| ![Financial Analytics](screenshots/financial-analytics.png) | ![Settings Panel](screenshots/settings-panel.png) |

---

## 👨‍💻 Developer Note
Designed and built end-to-end by analyzing real-world operational workflows of a local hair salon. Available for live demonstration and architectural discussion during interviews.
