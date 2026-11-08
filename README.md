# 🏦 UniCredit – Online Banking System

<p align="center">
  <b>A Modern Full-Stack Digital Banking Application</b>
</p>

<p align="center">
  A secure and user-friendly online banking platform designed to simplify financial operations through digital technology.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Framework-Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
</p>

---

## 📌 Overview

**UniCredit** is a full-stack online banking application developed using the **MERN Stack (MongoDB, Express.js, React.js, and Node.js)** as an Undergraduate Major Project.

The application aims to transform traditional banking operations into a convenient digital experience by enabling customers to manage their finances, perform transactions, apply for financial services, and access essential banking features online.

It also provides dedicated dashboards for administrators, managers, and clerks to streamline banking operations, application verification, and approval workflows.

## ✨ Key Features

- 🔐 **User Authentication** – Registration and login functionality.
- 💸 **Fund Transfers** – Perform online banking transactions.
- 🧾 **Transaction History** – View and track transaction records.
- 🏦 **Loan Management** – Apply for loans and track approval status.
- 💳 **Credit Card Services** – Submit and manage credit card applications.
- 📄 **Cheque Management** – Online cheque applications and verification.
- 🛡️ **Insurance Management** – Explore insurance plans and submit applications.
- ⚡ **Bill Payments** – Electricity and water bill payment services.
- 📱 **Mobile Recharge** – Convenient mobile recharge functionality.
- 👥 **Role-Based Dashboards** – Dedicated interfaces for different user roles.
- 🎧 **Helpdesk Support** – Access customer assistance.

## 👥 User Modules

| Module | Functionalities |
|---|---|
| 👨‍💼 Admin | Manage managers, clerks, customers, loans, credit cards, and insurance operations. |
| 📊 Manager | Approve or reject loan, credit card, insurance, and cheque applications; manage clerks. |
| 🧑‍💻 Clerk | Verify cheque applications and monitor customer accounts and transactions. |
| 👤 Customer | Manage accounts, transfer funds, apply for loans and cards, pay bills, and view transaction history. |

## 🛠️ Technology Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Development Tools
- Visual Studio Code
- Git
- GitHub

## 🏗️ Application Architecture

The application follows a full-stack architecture:

```text
          CLIENT SIDE
              |
          React.js
              |
          HTTP Requests
              |
       EXPRESS.JS API
              |
           NODE.JS
              |
          MONGODB
              |
       DATABASE STORAGE
```

## 📂 Project Structure

```text
UniCredit/
│
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── package.json
│
├── docs/
│   └── Project-Documentation.pptx
│
├── README.md
└── .gitignore
```


## ⚙️ Installation & Setup

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/unicredit-banking-app.git
```

### 2. Navigate to the Project

```bash
cd unicredit-banking-app
```

### 3. Install Dependencies

For the frontend:

```bash
cd frontend
npm install
```

For the backend:

```bash
cd ../backend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

Add any additional environment variables required by your actual application. Never commit real credentials or secrets.

### 5. Run the Application

Start the backend and frontend using the development scripts defined in their respective `package.json` files.

```bash
npm run dev
```

*Make sure the script names and commands match your actual project configuration.*

## 📸 Screenshots

Suggested screenshots:

- Login Page
- Home Page
- Customer Dashboard
- Admin Dashboard
- Manager Dashboard
- Clerk Dashboard
- Loan Management
- Credit Card Management
- Transaction History

<!-- Add your screenshots here -->

## 🔮 Future Enhancements

- 🤖 AI-powered chatbot for customer support.
- 🔍 Advanced fraud detection mechanisms.
- 📊 Predictive analytics for personalized banking.
- 📱 Dedicated Android and iOS applications.
- 🌍 International transactions with multi-currency support.
- 🔒 Biometric authentication.
- 🎙️ Voice command integration.
- 💡 AI-powered savings and investment recommendations.

## 🎓 Academic Project

Developed as an **Undergraduate Major Project** by students of the Department of Computer Science & Applications.

**Institution:** Christ Nagar College, Maranalloor, Trivandrum.

## 👩‍💻 Project Contributors

- Adithya SM
- Amritha Sai S
- Arya PL
- Gadha Prakash
- Nandhana Anil

## ⚠️ Disclaimer

UniCredit is an academic project developed for educational and demonstration purposes. It is not affiliated with any official banking institution and is not intended for handling real financial transactions or sensitive customer banking information.

## ⭐ Support

If you find this project interesting, consider giving the repository a ⭐ on GitHub!

---

<p align="center">
  <b>UniCredit – Banking Made Simpler. Banking Made Digital. 🏦</b>
</p>

<p align="center">
  Built with ❤️ using the MERN Stack.
</p>
