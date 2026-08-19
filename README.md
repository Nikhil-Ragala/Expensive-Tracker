#  Expense Management System

A full-stack **Expense Management System** built using the **MERN stack** — MongoDB, Express.js, React.js, and Node.js.

The application allows users to securely manage their expenses, track transactions, analyze spending patterns, and view their financial activity through an interactive dashboard.

---

##  Project Overview

The Expense Management System is a web-based application designed to simplify daily expense tracking and financial management.

Users can create an account, securely log in, add expenses, update or delete transactions, categorize spending, and monitor their financial activity through a responsive dashboard.

This project demonstrates practical implementation of **full-stack development, REST APIs, authentication, database management, CRUD operations, and frontend-backend integration**.

---

##  Objectives

- Simplify daily expense tracking.
- Provide an organized view of financial transactions.
- Help users understand their spending patterns.
- Allow users to create, update, and delete expenses.
- Provide visual insights into spending.
- Build a responsive and user-friendly MERN application.

---

##  Features

###  User Authentication

- User registration and login
- JWT-based authentication
- Password hashing using bcrypt
- Protected user-specific data
- User avatar selection

###  Expense Management

- Add new transactions
- View transaction history
- Edit existing transactions
- Delete transactions
- Track transaction amount
- Track transaction date
- Categorize expenses
- Add transaction descriptions

###  Dashboard & Analytics

- Total expense overview
- Recent transaction history
- Category-based expense analysis
- Visual representation of expenses
- Interactive charts
- Spending pattern analysis

###  Responsive User Interface

- Responsive React.js interface
- Clean dashboard
- Reusable React components
- Responsive layouts
- Interactive UI elements
- Animated background effects using TSParticles

---

##  Technical Architecture

### Frontend

The frontend is developed using **React.js** and provides the user interface for authentication, transaction management, and expense visualization.

Technologies and libraries include:

- React.js
- Redux
- Axios
- React Bootstrap
- Material Icons
- React Datepicker
- Moment.js
- TSParticles
- Unique Names Generator

### Backend

The backend is developed using **Node.js and Express.js** and provides RESTful APIs for authentication and transaction management.

Technologies include:

- Node.js
- Express.js
- JWT
- bcrypt
- Mongoose
- CORS
- Helmet
- Morgan
- dotenv

### Database

The application uses **MongoDB** for storing:

- User information
- Authentication data
- Expense transactions
- Transaction categories

**Mongoose** is used for schema definition and database interaction.

---

##  Application Architecture

```text
                    ┌─────────────────┐
                    │      User       │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │ React Frontend  │
                    │                 │
                    │ Authentication  │
                    │ Dashboard       │
                    │ Transactions    │
                    │ Analytics       │
                    └────────┬────────┘
                             │
                         REST APIs
                             │
                             ▼
                    ┌─────────────────┐
                    │ Express + Node  │
                    │     Backend     │
                    │                 │
                    │ Auth APIs       │
                    │ Transaction API │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │  MongoDB Atlas  │
                    │                 │
                    │ Users           │
                    │ Transactions    │
                    └─────────────────┘

                    Expensive-Tracker/
│
├── backend/
│   ├── controllers/
│   ├── DB/
│   ├── models/
│   ├── Routers/
│   ├── config/
│   │   └── config.env        # Local only - not committed
│   │
│   ├── app.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── Components/
│   │   ├── Pages/
│   │   ├── utils/
│   │   └── ...
│   │
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
└── README.md
##  Author

### Nikhil Ragala

**B.Tech — Aerospace Engineering**  
**Indian Institute of Technology Madras**

🔗 **GitHub:** [Nikhil Ragala](https://github.com/Nikhil-Ragala)

---

##  Repository

If you found this project useful, consider giving the repository a ⭐.

🔗 **Repository:** [Expense Tracker](https://github.com/Nikhil-Ragala/Expensive-Tracker)
