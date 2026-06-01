# 💰 MS Trackify – Expense Tracker App

[![Stars](https://img.shields.io/github/stars/Magan248/TrackifyApp?style=social)](https://github.com/Magan248/TrackifyApp/stargazers)

Simple aur responsive **Expense Tracker Application** built with **React.js (Vite)**, jo users ko expenses add, manage, filter aur track karne mein madad karta hai.

## 🔗 Important Links

🌐 Live Site: https://mstrackify.netlify.app/
💻 GitHub Profile: https://github.com/maganstackforge
📂 Project Repository: https://github.com/maganstackforge/TrackifyApp
👤 LinkedIn: https://linkedin.com/in/maganstackforge
📧 Email: magan.stackforge@gmail.com

---

## 📂 Project Structure

TrackifyApp/
├── node_modules/
├── public/
│ ├── \_redirects
│ └── favicon.webp
├── src/
│ ├── assets/
│ └── screenshots/
│ ├── components/
│ │ ├── About.jsx
│ │ ├── Contact.jsx
│ │ ├── ContextMenu.jsx
│ │ ├── ExpenseForm.jsx
│ │ ├── ExpenseTable.jsx
│ │ ├── Footer.jsx
│ │ ├── Header.jsx
│ │ ├── Home.jsx
│ │ ├── Input.jsx
│ │ ├── SelectInput.jsx
│ │ └── Sidebar.jsx
│ ├── hooks/
│ │ ├── useFilter.js
│ │ └── useLocalStorage.js
│ ├── App.css
│ ├── App.jsx
│ ├── index.css
│ └── main.jsx
├── .gitignore
├── package.json
├── package-lock.json
├── tailwind.config.js ← agar Tailwind use kar rahe ho
├── vite.config.js
└── README.md

---

## 🚀 Features

• Quick Add: Category, Title aur Amount ke sath naye expenses jodein.

• Context Menu Management: Table par click karke expenses ko asaani se Edit & Delete karein.

• Smart Filtering: Expenses ko category ke basis par filter karein.

• Advanced Sorting: Alphabetically ya Amount ke basis par data sort karein (with Clear Sort option).

• Data Persistence: Browser close hone par bhi data safe rahega (LocalStorage integrated).

**Fully Responsive Design:**
Seamless layout across all devices, from large desktops to mobile screens.

## 🛠️ Tech Stack

• Frontend: React.js (Vite)

• Styling: TailwindCSS

• State & Logic: Custom React Hooks (useFilter, useLocalStorage)

• Storage: LocalStorage API

• Code Quality: ESLint & Prettier

---

## ⚙️ Getting Started

1. Repository clone karo:

   ```bash
   git clone [https://github.com/maganstackforge/TrackifyApp.git](https://github.com/maganstackforge/TrackifyApp.git)

   ```

# Project directory me jao:

    cd TrackifyApp

# Dependencies install karo:

npm install

# Development server run karo:

npm run dev

# Browser me http://localhost:5173/home

📸 Screenshots

**Home Page**
![HomePage](src/assets/screenshots/DesktopHome.png)

**Add Expense**
![AddDetails](src/assets/screenshots/DesktopAddDetails.png)

**Show & Manage Expenses (Edit/Delete via Context Menu)**
![ShowDetails](src/assets/screenshots/DesktopShowDetailsWithEditDelete.png)

**Update Expense**
![UpdateDetails](src/assets/screenshots/DesktopUpdateDetails.png)

**About Us in Mobile View**
![MobileAboutPage](src/assets/screenshots/MobileAbout.png)

**Show & Manage Expenses (Edit/Delete via Context Menu) in Mobile View**
![MobileDetailsPage](src/assets/screenshots/MobileDetailspage.png)

**Contact Us in Mobile View**
![MobileContactPage](src/assets/screenshots/MobileContact.png)

## 📜 Version Control & Contribution

- Project is maintained with **Git & GitHub** using proper version control practices.
- Authentic and meaningful commit messages are used throughout development.
- Example commit types:
  - `feat:` → 'Create \_redirect file in public folder'
  - `fix:` → for bug fixes
  - `refactor:` → refactor: rename sidebar file for consistency
  - `style:` → update sidebar padding and button color
  - `test:` → for adding/updating tests
  - `chore:` → 'remove tableDemo.jsx and lazy import file and images and remove unused styles'

📌Future Enhancements
• [x] 🔐 User Authentication (Login/Signup via Firebase or Auth0)

• [x] 📤 Export data to CSV/PDF

• [x] 📊 Rich Interactive Analytics (Graphs & Charts using Recharts)

• [x] 🌙 Dark Mode Support

👨‍💻 Author

Magan Singh
