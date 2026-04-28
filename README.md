# 🗳️ Online Voting System — Campus Elections

A full-stack web application that digitizes campus-level elections for students, faculty, and administration. Built as a Database Systems project.

## 👥 Contributors
- AyeshaNoor_2575 | HiraKhalid_2594 | AreebaNoor_2562

## 🔧 Tech Stack
| Layer     | Technology                     |
|-----------|-------------------------------|
| Backend   | Node.js + Express.js          |
| Database  | Microsoft SQL Server (MSSQL)  |
| Auth      | JWT + bcryptjs                |
| Frontend  | HTML, CSS, Vanilla JavaScript |
| Email     | Nodemailer                    |

## 📁 Features
- Role-based access: Student, Faculty, Management, Admin
- Secure user registration & login with CNIC verification
- Campus & department-based voter eligibility
- Create, manage & participate in elections
- Candidate registration & real-time vote tracking
- Result viewing with vote-count analytics
- Admin dashboard for system management
- Email notifications via Nodemailer
- SQL triggers, stored procedures & constraints in schema

## 🗃️ Database Highlights
- Tables: Campuses, Departments, Users, Student_Details, Faculty_Details, Elections, Candidates, Votes
- Features: Triggers, constraints, identity columns, role-based checks

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- Microsoft SQL Server
- `.env` file with DB credentials

### Setup
git clone <repo-url>
cd Backend
npm install
# Configure .env with DB_SERVER, DB_NAME, DB_USER, DB_PASSWORD
npm run dev

### Frontend
Open frontend/index.html in a browser or serve with Live Server.

## 📡 API Endpoints
- POST /api/auth/register — Register new user
- POST /api/auth/login — Login
- GET  /api/elections — View elections
- POST /api/votes — Cast a vote
- GET  /api/admin — Admin management
