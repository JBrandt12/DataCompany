# DataCompany

# 📊 SignalsPath — Data Analytics Company Website

SignalsPath is a modern data analytics company offering full-service data intelligence and automation. This repository contains both the **frontend** (React + Vite) and **backend** (Go + Gin + MySQL) codebases.

---

##  Live Preview

🌐 [https://signalspath.crytpo-streets.com]

---

##  Tech Stack

| Area        | Stack                          |
|-------------|-------------------------------|
| Frontend    | React + Vite + Tailwind CSS   |
| Backend     | Go (Gin)                      |
| Database    | MySQL                         |
| DevOps      | Docker / Docker Compose       |


---

##  Core Features

###  Website Pages
- **Homepage** with hero banner and lead capture
- **About** – company mission and team
- **Pricing** – 3-tier plan model
- **Jobs** – list of openings with application form
- **Apply Page** – with resume upload and technical screening
- **Contact Page** – email inquiry form
- **How It Works** – showcases stack (Python, Go, SQL, etc.)
- **Admin-only route logger** – tracks anonymous visitors

---

### 🛠 Backend Services

| Endpoint         | Description                              |
|------------------|------------------------------------------|
| `POST /send-email` | Handles contact form messages           |
| `POST /application` | Accepts job applications + file upload |
| `POST /home` (or `/log-visit`) | Tracks anonymous visitor activity   |

---

###  Resume Upload

- Accepts `.pdf .doc`,
