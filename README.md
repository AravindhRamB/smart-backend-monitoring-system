#Smart Backend Monitoring & Alert System (SBMAS)

A scalable backend monitoring system built using **Node.js, Express, PostgreSQL, and Docker** to track API health, performance metrics, and trigger alerts for abnormal behavior.

---

## Features

- ✅ API health monitoring
- ✅ Request & response time tracking
- ✅ Error logging
- ✅ PostgreSQL-based log storage
- ✅ Dockerized environment
- ✅ Scalable architecture
- ✅ Ready for alert integrations (Email / Slack)
- ✅ Clean MVC structure

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| Node.js (v20 LTS) | Backend runtime |
| Express.js | REST API framework |
| PostgreSQL | Database |
| Sequelize | ORM |
| Docker | Containerization |
| DBeaver | DB Management |
| Winston | Logging |

---

## 📁 Project Structure
src/
├── config/ # DB & logger configs
├── controllers/ # API logic
├── middlewares/ # Request handlers
├── models/ # DB models
├── routes/ # API routes
├── services/ # Business logic
├── utils/ # Helpers
├── app.js # Express app
└── server.js # Entry point

## Setup Instructions

### Clone the repo
```bash
git clone https://github.com/yourusername/smart-backend-monitoring-system.git
cd smart-backend-monitoring-system

### Install Dependencies
npm install

### RUN Project 
npm run dev


