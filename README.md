# Personal Expense Tracker Web Application

## 1. Project Overview

The Personal Expense Tracker is a web-based application developed to help users manage and track their daily expenses.

Users can register, log in, add expenses, view transactions, update or delete expense records, and monitor their spending through monthly summaries and category-wise charts.

## 2. Problem Statement

Managing daily expenses manually can be difficult. People may forget their transactions and find it challenging to understand their spending habits.

This application provides a digital platform to record expenses and monitor spending in an organized way.

## 3. Project Objectives

- Simplify personal expense management.
- Maintain expense records digitally.
- Allow users to manage their own expenses.
- Display monthly spending summaries.
- Provide category-wise expense analysis.

## 4. Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js, Vite |
| Styling | Tailwind CSS |
| Backend | Python, FastAPI |
| Database | PostgreSQL |
| ORM | SQLAlchemy |
| Database Migration | Alembic |
| Authentication | JWT |
| Charts | Chart.js |
| Frontend Deployment | Vercel |
| Backend Deployment | Render |

## 5. Main Features

- User registration and login.
- JWT-based authentication.
- Add new expenses.
- View expense records.
- Update existing expenses.
- Delete expenses.
- Expense categorization.
- Monthly spending summaries.
- Category-wise expense charts.

## 6. Project Architecture

The application consists of three main components:

**Frontend:** Provides the user interface and communicates with backend APIs.

**Backend:** Handles authentication, API requests, and expense-related operations.

**Database:** Stores user information and expense records.

## 7. Database Structure

### Users Table
- id
- name
- email
- hashed_password

### Expenses Table
- id
- user_id
- amount
- category
- date
- description

## 8. Live Application Links

**Frontend Deployment:**

https://personal-expense-tracker-frontend-sigma.vercel.app/

**Backend Deployment:**

https://personal-expense-tracker-backend-jdox.onrender.com/

**API Documentation:**

https://personal-expense-tracker-backend-jdox.onrender.com/docs

## 9. GitHub Repositories

**Frontend Repository:**

https://github.com/ShraddhaThitte28/Personal_Expense_Tracker_Frontend

**Backend Repository:**

https://github.com/ShraddhaThitte28/Personal_Expense_Tracker_Backend

## 10. Conclusion

The Personal Expense Tracker provides a simple and convenient way to manage personal expenses. Developing this project provided practical experience in full-stack web development, REST API integration, database management, authentication, CRUD operations, and application deployment.