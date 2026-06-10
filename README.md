# 🎮 ZYNNN STORE - Game Top Up & Boosting Platform

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

ZYNNN STORE is a web-based front-end application that provides microtransaction services for online games, such as Diamond Top-Ups and Rank Boosting. This project features a modern Dark Mode design coupled with comprehensive interactive functionalities.

---

## 🎓 Academic Context / Background

This repository was developed and submitted to fulfill the **Final Project for the Web-Based Programming Course**. 

The main focus of this system's development is the implementation of a responsive User Interface, dynamic DOM (Document Object Model) manipulations, and client-side state management without relying on heavy JavaScript frameworks. The system is designed to provide a seamless navigation experience resembling a Single Page Application (SPA) purely through Vanilla JavaScript.

---

## ✨ Key Features

1. **Smart Multi-Language System (i18n):** 
   Supports both Indonesian and English. The system is integrated with the browser's `localStorage`, ensuring that once a user selects a language on one page, all other pages will automatically adapt to that preference without requiring a reload.
2. **Integrated Gamers Calculator:**
   Features a specialized utility calculator (Target Win Rate Calculator & Win/Lose Detail Checker) utilizing pure client-side mathematical logic and validation.
3. **Checkout Simulation & Data Persistence:**
   User orders (Top Up / Boosting) are validated and temporarily saved using `localStorage`. Users can track their "Invoice Code" on the Order Check page, which dynamically retrieves and displays their billing receipt.
4. **Dynamic Form Validation (Regex):**
   Prevents spam or invalid inputs (e.g., blocking WhatsApp numbers filled with repeating identical digits like `08888888888`).
5. **Modern & Responsive UI:**
   Built using the Utility-First CSS paradigm from Tailwind. The interface ensures cross-device accessibility (Desktop, Tablet, and Mobile).

---

## 🛠️ Tech Stack

* **Markup:** HTML5 (Semantic & Structured)
* **Styling:** Tailwind CSS (via CDN for rapid prototyping) & Custom Scrollbar CSS.
* **Interactive Logic:** Vanilla JavaScript (ES6+).
* **Iconography:** FontAwesome 6.
* **Data Storage (Mock DB):** Browser Web Storage API (`localStorage`).

---

## 📂 Directory Structure

```text
📦 TugasAkhir
 ┣ 📂 images/               # Image assets, logos, banners, and game thumbnails
 ┣ 📜 index.html            # Home Page (Game Catalog)
 ┣ 📜 mobile-legends.html   # Mobile Legends Category Page
 ┣ 📜 diamond-mlbb.html     # MLBB Diamond Order Form Page
 ┣ 📜 joki-mlbb.html        # MLBB Rank Boosting Order Form Page
 ┣ 📜 freefire.html         # Free Fire Diamond Order Form Page
 ┣ 📜 cek-pesanan.html      # Invoice Tracking / Order Search Page
 ┣ 📜 cek-transaksi.html    # Final Receipt / Invoice Details Page
 ┣ 📜 kalkulator.html       # WR & Win/Lose Calculator Utility Page
 ┗ 📜 README.md             # Project Documentation