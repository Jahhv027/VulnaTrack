# 🛡️ VulnaTrack

**VulnaTrack** is a powerful vulnerability scanning dashboard built for modern DevOps environments. Developed using **Python**, **Express**, and **React**, VulnaTrack empowers engineering teams to detect, track, and resolve security issues in real time—directly from their CI/CD pipelines.

Designed for seamless integration and rapid response, VulnaTrack provides actionable insights, real-time alerts, and historical vulnerability trends to ensure secure software delivery at scale.

## 📌 Features

- 🔍 **Real-Time Vulnerability Detection**:
  - Integrated with CI/CD pipelines (Jenkins, GitHub Actions, GitLab CI)
  - Scans for OWASP Top 10, CVEs, and custom security rules
  - Live updates on new findings with severity classification

- 📊 **Intuitive Dashboard**:
  - Centralized view of vulnerabilities across repositories
  - Charts and graphs showing trends by date, type, and severity
  - Drill-down reports by commit, branch, or developer

- 🧩 **Issue Tracking Integration**:
  - Auto-create tickets in Jira, GitHub, or GitLab
  - Assign vulnerabilities to dev team members
  - Track remediation status within the dashboard

- 🔐 **Role-Based Access**:
  - Admin, security lead, and developer roles
  - JWT-based authentication and session management
  - Audit logs for all activity and changes

- 🚀 **DevOps-Ready & Scalable**:
  - RESTful API for integration with external tools
  - Dockerized microservices for scalable deployment
  - Webhooks for custom automation on detection

## 🛠️ Tech Stack

- **Frontend**: React.js, Chart.js, Tailwind CSS
- **Backend**: Python (FastAPI), Node.js (Express)
- **Databases**: MongoDB, Redis
- **Containers**: Docker, Docker Compose
- **Security**: JWT, HTTPS, OAuth2 (optional)

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- Node.js 18+
- Docker & Docker Compose
- MongoDB & Redis instances

### Clone & Deploy

```bash
git clone https://github.com/your-username/vulnatrack.git
cd vulnatrack
docker-compose up --build
