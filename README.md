# 📘 Chama360 – Smart Chama Management Platform

Chama360 is a full-stack web application designed to help informal savings groups ("chamas") manage their financial activities more transparently and efficiently.

## 🌍 Overview

Chama360 empowers members and administrators of savings groups to:
- Track contributions and loan records
- Schedule and manage meetings
- Vote on decisions
- View financial reports
- Receive automated reminders and updates

---

## 🎯 Objectives

- Digitize chama record keeping 📊  
- Provide secure, role-based access 🔐  
- Improve transparency and trust ✅  
- Offer actionable insights with reports 📈  
- Enable remote access via web 🌐

---

## 👥 Target Users

- Chama members
- Treasurers and group admins
- Youth savings groups
- Saccos and microfinance circles
- Investment clubs

---

## 🧩 Core Features (MVP)

| Feature             | Description |
|---------------------|-------------|
| 👥 Auth & Roles      | Login system with Member, Treasurer, Admin roles |
| 💰 Contributions     | Add, edit, and view member contributions |
| 💳 Loan Tracking     | Record loan requests, approvals, and balances |
| 🗳 Voting            | Members can vote on proposals or loan approvals |
| 📊 Reports           | View charts and summaries of group finances |
| 🔔 Notifications     | Reminders for contributions, meetings, and deadlines |

---

## 🛠 Tech Stack

### Frontend
- React + Tailwind CSS
- Option to upgrade to React later

### Backend
- Django + Django REST Framework
- PostgreSQL database
- JWT/Django Auth for security

### Deployment
- Frontend: GitHub Pages / Netlify
- Backend: Render / Railway

---

## 🚀 Getting Started

### 🔧 Backend Setup
```bash
git clone https://github.com/yourusername/chama360-backend.git
cd chama360-backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
