<div align="center">

# ![Logo](./readme_images/logo.png "Learnify Logo") LEARNIFY

**Full Stack Web Application**

[![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Issues](https://img.shields.io/github/issues/your-username/learnify_full_stack_application)](https://github.com/your-username/learnify_full_stack_application/issues)
[![Forks](https://img.shields.io/github/forks/your-username/learnify_full_stack_application)](https://github.com/your-username/learnify_full_stack_application/network)

</div>

---

## 📌 About the Project

Learnify is a **full-stack Java web application** for online learning.  
It allows students to **purchase, enroll, and track courses** while providing trainers with **dashboards to manage content efficiently**.

**Key Highlights:**

- Developed with **JSP/Servlets** + **JDBC** + **MySQL** for secure data handling.
- Dynamic content delivery for scalable user interactions.
- RESTful API integration for modular architecture.
- Trainer dashboards to monitor courses and users.

---

## 🚀 Features

- User registration & authentication
- Role-based access (Admin / Instructor / Student)
- Course management: create, update, delete
- Profile management (images, progress tracking)
- Interactive dashboards
- Dynamic content delivery
- RESTful API integration

---

## 🛠️ Tech Stack

| Layer      | Technology                                     |
| ---------- | ---------------------------------------------- |
| Backend    | Java, JSP, Servlets, JDBC, MySQL               |
| Frontend   | HTML, CSS, JavaScript, React/Angular(optional) |
| Build Tool | Maven                                          |
| Deployment | Docker, Heroku, AWS, Render                    |

---

## 🗂️ Folder Structure

```
# 🧠 Advanced Java Web Project Structure

```bash
Root Folder (App)/
├── static/
│    ├── css/
│    │    └── * All CSS files *
│    ├── js/
│    │    └── * All JS files *
│    └── media/
│         ├── images/
│         │    └── * All images *
│         └── videos/
│              └── * All videos *
├── WEB-INF/
│    ├── src/
│    │    ├── controllers/
│    │    │    └── * Java controller classes *
│    │    ├── filters/
│    │    │    └── * Java filter classes *
│    │    ├── models/
│    │    │    └── * Java model classes *
│    │    ├── utils/
│    │    │    └── * Java utility classes *
│    │    └── listeners/
│    │         └── * Java listener classes *
│    ├── lib/
│    │    └── * All required JAR libraries *
│    ├── pages/
│    │    └── * All JSP files *
│    └── uploads/
│         └── * User-specific folders (named by email) containing user data *
├── queries.db
│    └── * SQLite database file for creating tables and sample data *
└── readme-image/
     └── * All images used in README files *

```

---

## 💾 User Data Storage

After registration, each user gets a dedicated folder under `APPLICATION_USERS`.  
This folder stores all important user-specific data:

- Course videos
- Profile images
- Other content

> Each folder is named after the username for organized and secure storage.

---

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/learnify_full_stack_application.git
```
