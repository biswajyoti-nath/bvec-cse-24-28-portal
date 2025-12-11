# BVEC CSE 2024–2028 Portal

A fully responsive, client-side web application built for the **CSE Batch 2024–28** of Barak Valley Engineering College (BVEC).  
The project demonstrates dynamic UI rendering, data handling in the browser, DOM manipulation, and responsive frontend design using modern web technologies.

**Live Website:** https://biswajyoti-nath.github.io/cse24-28/

---

## 📌 Professional Overview

### ⭐ Core Highlights
- Designed and implemented a **birthday management system** with:
  - Add, search, and month-based filter features  
  - LocalStorage persistence  
  - Automated *Next Birthday* and *Next 3 Birthdays* calculations  
- Built a fully responsive UI using **Bootstrap 5**, **custom CSS**, and **AOS animations**  
- Implemented clean DOM updates, HTML escaping, data sorting, and reusable utility functions  
- Deployed the project using **GitHub Pages**  
- Follows modular JavaScript structure for clarity and maintainability

---

## 🛠️ Tech Stack
- **HTML5**, **CSS3**, **JavaScript (ES6)**
- **Bootstrap 5.3**
- **AOS (Animate On Scroll)**
- **LocalStorage API**
- **GitHub Pages**

---

## 📁 Project Structure
```

cse24-28/
│
├── index.html         # Main UI
├── style.css          # Custom dark theme styles
├── app.js             # Logic for birthdays, rendering, utilities
└── assets/            # Images (logos, group photo, WhatsApp DP, profile)

````

---

## 🚀 Features

### 🎂 Birthday Manager
- Add new birthdays using a modal form  
- Prevents duplicate names & validates inputs  
- Search by name  
- Month-wise filters (Jan–Dec)  
- Displays next upcoming birthday + days remaining  
- Shows next 3 upcoming birthdays  
- Stores data locally without any backend  

### 🎉 UI Features
- Clean hero section with batch image  
- WhatsApp DP showcase  
- Smooth animations (AOS)  
- Fully responsive and mobile-friendly design  

### 🔗 Quick Links
- BVEC Official Website  
- CSE Department Page  
- ASTU University Portal  

---

## 🧪 Running the Project (Local)

### Option A — Open directly
Open `index.html` in any browser.

### Option B — Via local server (recommended)
```bash
python -m http.server 8000
# Open http://localhost:8000
````

---

## ⚙️ Configurations (in `app.js`)

Max saved birthdays:

```js
const MAX_BIRTHDAYS = 60;
```

LocalStorage key:

```js
const STORAGE_KEY = 'cse24_birthdays_v1';
```

Seed data is loaded automatically on first use.

---

## 🔄 Resetting Data

1. Open Developer Tools
2. Go to **Application → Local Storage**
3. Delete `cse24_birthdays_v1`
4. Refresh page → data resets to seed values

---

## 📌 Future Enhancements

* Add student profile pictures
* Export/Import birthdays as JSON
* Age calculation + zodiac signs
* Editable entries (admin mode)
* Calendar sync (Google Calendar)
* Announcements section for department updates

---

# 🎉 The Fun Story (Optional Reading)

This project originally started as a **fork from a friend who was learning JavaScript**.
The plan was simple: *clone, look around, maybe fix something small*.

Instead…

It somehow turned into a **full-blown class website with:**

* animations
* responsive UI
* a complete birthday system
* filtering, searching, sorting
* GitHub Pages deployment

What began as:

> “Let me check my friend's repo.”

accidentally became:

> “Oops… I built a full portal for our entire batch.”

Sometimes projects grow on their own — and that’s how this one was born.

---

## ❤️ Credits

Made for the **CSE Batch 2024–28**, BVEC.
Thanks to the original small JS repo that inspired a far bigger project.
