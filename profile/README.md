## Hi there 👋

# 🌱 Health Innovation App - OISHII LIFE PROJECT 1.0

## Badge for Frontend
![GitHub repo size](https://img.shields.io/github/repo-size/CAPSTONE-PROJECT-1-0/frontend)
![Contributors](https://img.shields.io/github/contributors/CAPSTONE-PROJECT-1-0/frontend)
![GitHub stars](https://img.shields.io/github/stars/CAPSTONE-PROJECT-1-0/frontend?style=social)

<br>

## Badge for Backend
![GitHub repo size](https://img.shields.io/github/repo-size/CAPSTONE-PROJECT-1-0/backend)
![Contributors](https://img.shields.io/github/contributors/CAPSTONE-PROJECT-1-0/backend)
![GitHub stars](https://img.shields.io/github/stars/CAPSTONE-PROJECT-1-0/backend?style=social)

<br>

## Badge for Machine Learning
![GitHub repo size](https://img.shields.io/github/repo-size/CAPSTONE-PROJECT-1-0/machine_learning)
![Contributors](https://img.shields.io/github/contributors/CAPSTONE-PROJECT-1-0/machine_learning)
![GitHub stars](https://img.shields.io/github/stars/CAPSTONE-PROJECT-1-0/machine_learning?style=social)

## 💡 Overview

Welcome to our Capstone Project developed as part of the **Coding Camp Powered by DBS Foundation**!  
This application is built to tackle real-world challenges in the health sector through innovative digital solutions.

Our project aims to **empower communities with accessible, smart, and scalable health technology**.

---

## 🚀 Tech Stack

This project is a full-stack application composed of three main components:

| Layer                   | Technology Used                     |
|-------------------------|-------------------------------------|
| **Frontend**            | [Next.js](https://nextjs.org/)      |
| **Backend API**         | [Hapi.js](https://hapi.dev/) |
| **Machine Learning API**| [Flask](https://flask.palletsprojects.com/) |

---

## 👥 Team Members

We are a team of 6 passionate developers and data scientists, collaborating across different domains:

### 🧠 Machine Learning Engineers
- Yuda Reyvandra Herman (MC189D5Y0450)
- Damianus Christopher (MC189D5Y0821)
- Reksi Hendra Pratama (MC189D5Y0840)

### 💻 Fullstack Developers (FE/BE)
- Muhammad Wildan Nur Romadhoni (FC723D5Y1622)
- Marsella Vindriani (FC315D5X2256)
- Miftahurrohman (FC464D5Y1026)

---

## 🔧 Project Structure (Polyrepo)
This project structure is made with polyrepo or can be called multi repo. We use this project structure so that each team can focus on their respective repositories without worrying about changes to other repositories.

```markdown
## Frontend Structure 

```Tree
├── .env.local        # Configuration Local Environment
├── .gitignore        # Ingnoring File by Git
├── next.config.js    # Configuration Next.js
├── package-lock.json # Lock file for dependency (npm)
├── package.json      # Project and Dependency Information 
├── postcss.config.js # Configuration PostCSS
├── README.md         # File README ini
├── tailwind.config.js# Configuration Tailwind CSS (Optional)
├── tsconfig.json     # Configuration TypeScript (Optional)
└── src/
    ├── app/              # Min Directory for App Router
    │   ├── (group)/        # Example rute group  (optional)
    │   │   ├── page.js   # Main Page for this group 
    │   │   └── layout.js # Layout for this group (optional)
    │   ├── api/            # Endpoint API routes
    │   │   └── ...
    │   ├── components/     # reusable components 
    │   │   └── ...
    │   ├── layout.js       # Layout app root 
    │   ├── page.js         # Main Page App (/)
    │   └── template.js     # Template for maintain state between route (optional)
    ├── assets/           # static Assets (image, font, etc.)
    │   └── ...
    ├── lib/              # Utils, helper functions, External Configuration
    │   └── ...
    ├── styles/           # Styles global or module CSS/SCSS
    │   ├── global.css
    │   └── ...
    └── ...               # Directory or other file as required
```



