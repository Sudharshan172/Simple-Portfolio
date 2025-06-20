# 🌐 Personal Portfolio Website

A modern, responsive portfolio website built with **React.js** and **Tailwind CSS**, designed to showcase my skills, projects, experience and contact information. Integrated with **EmailJS** to handle contact form submissions without a backend.

## 🚀 Live Demo

👉 [View Live Site](https://portfolio-ydke.onrender.com/)

---
## ✨ Features

- ⚡ Fast and responsive UI using **React + Tailwind CSS**
- 📱 Fully mobile-friendly and cross-browser compatible
- 🧾 Dynamic sections:
  - Hero / Landing
  - About Me
  - Projects & Work
  - Contact Me
- 📬 Integrated **EmailJS** for sending form submissions directly to my email
- 🔐 Environment variables used to protect sensitive keys (`.env`)

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| [React](https://reactjs.org/) | Frontend library |
| [Vite](https://vitejs.dev/) | Build tool for development |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first CSS framework |
| [EmailJS](https://www.emailjs.com/) | Contact form email integration |
| [Lucide Icons](https://lucide.dev/) | Icon library |
| [GitHub Pages / Vercel / Netlify](https://vercel.com/) | Deployment |

---

## 📁 Folder Structure

```bash
portfolio/
├── public/
│   ├── resume.pdf
├── src/
│   ├── assets/             # Static files (images, icons, etc.)
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── MobileMenu.jsx
│   │   └── LoadingScreen.jsx
│   ├── sections/
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── Projects.jsx
│   │   └── Contact.jsx
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── .env
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── README.md
└── eslint.config.js

