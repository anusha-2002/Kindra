# 🏦 CauseBank

A crowdfunding platform designed for verified charitable organizations. Donors can support causes they care about while organizations manage transparent fundraising campaigns.

## What It Does

This platform connects donors with verified charitable organizations. Charities create fundraising campaigns after going through a verification process that includes tax ID validation and registration documentation. Donors can browse causes by category, make secure donations through Stripe, and track their contribution history.

The platform includes features like bookmarking favorite causes, real-time donation updates, and automated receipt generation. Organizations get a dedicated dashboard to manage their campaigns and track donations. The platform operates on a 5% transaction fee model.

## Tech Stack

**Backend**: Spring Boot, PostgreSQL, JWT Authentication, AWS (S3, EC2, RDS)  
**Frontend**: React, Material-UI, Redux  
**Payment**: Stripe API  
**DevOps**: Docker, GitHub Actions, Swagger

## How to Run

**Prerequisites**: Java 11+, Node.js 14+, PostgreSQL, Docker

```bash
# Clone the repository
git clone <repository-url>

# Backend setup
cd backend
./mvnw clean install
./mvnw spring-boot:run

# Frontend setup (in new terminal)
cd frontend
npm install
npm start
```

**Using Docker**:

```bash
docker build -t causebank-backend ./backend
docker build -t causebank-frontend ./frontend
```

## Access Points

- Frontend: http://localhost:3000
- Backend API: http://localhost:8081
- API Documentation: http://localhost:8081/swagger-ui.html

## Key Features

**For Donors**: Browse verified causes, donate securely via Stripe, track donation history, bookmark favorite campaigns

**For Organizations**: Create and manage campaigns, set fundraising goals, monitor donations, receive payouts (95% after platform fee)

**For Admins**: Verify organizations, monitor transactions, maintain platform integrity

---

Built with Spring Boot & React
