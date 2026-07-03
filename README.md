# 💼 Job Portal Backend

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Backend-black?style=for-the-badge&logo=flask)
![REST API](https://img.shields.io/badge/REST-API-orange?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-Database-blue?style=for-the-badge&logo=sqlite)
![Git](https://img.shields.io/badge/Git-Version_Control-red?style=for-the-badge&logo=git)

A backend application for managing job applications through a clean RESTful architecture.

The system allows users to organize their job search by tracking applications, monitoring progress, filtering opportunities, and managing recruitment data efficiently.

---

# ✨ Features

- 💼 Job Application Management
- 🔍 Search & Filter
- 📄 CRUD Operations
- 📊 Application Status Tracking
- 🗄 SQLite Database
- ⚡ RESTful API Design
- 📦 Modular Backend Structure

---

# 🏗 Architecture

```
                Client
                  │
                  ▼
            Flask REST API
                  │
      ┌───────────┼───────────┐
      ▼           ▼           ▼
 Jobs      Companies     Status
                  │
                  ▼
               SQLite
```

---

# 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Framework | Flask |
| Database | SQLite |
| API Style | REST |
| Version Control | Git |

---

# 📂 Project Structure

```text
job-application-tracker/

├── app.py
├── routes/
├── models/
├── database/
├── static/
├── templates/
├── requirements.txt
└── README.md
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/neha-singh-dev/job-application-tracker.git
cd job-application-tracker
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
python app.py
```

Server starts on

```
http://127.0.0.1:5000
```

---

# 📡 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/jobs` | Retrieve all job applications |
| POST | `/jobs` | Create a new application |
| GET | `/jobs/<id>` | Retrieve a specific application |
| PUT | `/jobs/<id>` | Update an application |
| DELETE | `/jobs/<id>` | Delete an application |

---

# 💡 Skills Demonstrated

- Backend Development
- Flask
- REST API Design
- CRUD Operations
- Database Design
- Search & Filtering
- API Architecture
- Python Programming

---

# 🔮 Roadmap

Future improvements planned:

- 🔐 JWT Authentication
- 👤 User Accounts
- 🏢 Company Management
- 📅 Interview Scheduling
- 📎 Resume Upload
- 📈 Dashboard Analytics
- 🐘 PostgreSQL Migration
- ⚡ Django REST Framework Version
- ☁️ Cloud Deployment (Render / Railway)

---

# 👩‍💻 Author

**Neha Singh**

Backend Developer • Python • Django • Flask • REST APIs

GitHub: https://github.com/neha-singh-dev

---

⭐ If you found this project useful, consider giving it a star!
