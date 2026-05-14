
# Metro Management System 🚆

A full-stack web application designed to automate and simplify metro rail operations such as ticket booking, passenger management, station handling, fare management, and metro scheduling.

Built using **Node.js**, **Express.js**, **MySQL**, and a responsive frontend with **HTML, CSS, and JavaScript**.

---

# 📌 Problem Statement

Managing metro rail operations manually or using disconnected systems often leads to:

* Data redundancy
* Slow ticket booking processes
* Human errors
* Inefficient fare management
* Difficulty in maintaining passenger records
* Lack of centralized control

The **Metro Management System** solves these issues by providing a centralized and automated platform for managing metro services efficiently.

---

# 🎯 Objectives

* Automate metro rail operations
* Provide a user-friendly ticket booking system
* Manage stations, routes, schedules, and passengers efficiently
* Ensure secure payment processing
* Reduce manual effort and operational errors
* Build a scalable and maintainable system

---

# ✨ Features

## 👤 User Module

### 🔐 User Authentication

* User Registration
* Secure Login System
* Password encryption for security

### 🎫 Ticket Booking

* Book metro tickets between stations
* Select source and destination stations
* Automatic fare handling
* Generate travel records

### 💳 Payment Integration

* Integrated with Razorpay payment gateway
* Payment verification support
* Payment status tracking

### 🕒 Active Tickets

* View currently active tickets
* Tickets valid for the next 24 hours

### 📜 Travel History

* View previously completed journeys
* Access old ticket and payment records

### 📊 Travel Statistics

* Total trips completed
* Active tickets count
* Monthly fare expenditure tracking

---

## 🛠️ Admin Module

### 🚉 Station Management

* Add new stations
* Manage station details
* Assign stations to metro lines

### 🚇 Metro Line Management

* Create metro lines
* Connect stations with metro routes
* Maintain station order within lines

### 🕑 Schedule Management

* Manage arrival and departure timings
* View metro schedules

### 📋 Centralized Data Management

* Manage users, tickets, stations, schedules, and payments from one platform

---

# 🏗️ System Architecture

The project follows a **Three-Tier Architecture**:

## 1️⃣ Presentation Layer (Frontend)

Built using:

* HTML
* CSS
* JavaScript

Responsibilities:

* User interaction
* Responsive UI
* Sending API requests

---

## 2️⃣ Application Layer (Backend)

Built using:

* Node.js
* Express.js

Responsibilities:

* Business logic
* API handling
* Authentication
* Database communication

---

## 3️⃣ Database Layer

Built using:

* MySQL

Responsibilities:

* Data storage
* Query execution
* Data integrity
* Relationship management

---

# 🗄️ Database Design

The project uses multiple relational tables including:

* `users`
* `station`
* `ticket`
* `ticket_payment`
* `metro_line`
* `line_stations`
* `metro_schedule`

Key database concepts used:

* Primary Keys
* Foreign Keys
* Joins
* Relationships
* Optimized SQL Queries

---

# ⚙️ Technologies Used

## Frontend

* HTML
* CSS
* JavaScript

## Backend

* Node.js
* Express.js

## Database

* MySQL

## Payment Gateway

* Razorpay

## Development Tools

* VS Code

---

# 🔄 Workflow

1. User interacts with the frontend
2. Frontend sends requests to backend APIs
3. Backend processes requests
4. MySQL database stores/retrieves data
5. Backend sends response to frontend
6. User receives updated information

---

# 🔑 Important Functionalities

## ✔️ Secure Authentication

* Password hashing
* Protected user data

## ✔️ Real-Time Ticket Handling

* Instant booking and payment updates

## ✔️ REST API Integration

* Smooth frontend-backend communication

## ✔️ Payment Verification

* Razorpay signature verification support

## ✔️ Data Integrity

* Relational database constraints and validations

---

# 🧪 Testing

The following functionalities were tested successfully:

* User Registration
* Login Authentication
* Invalid Login Handling
* Ticket Booking
* Payment Processing
* Active Ticket Viewing
* Travel History
* Admin Station Management
* Metro Line Management
* Schedule Viewing
* Travel Statistics

---

# 📈 Results

* Reduced manual work
* Improved ticket booking efficiency
* Centralized metro data management
* Secure payment processing
* Faster access to schedules and travel data
* Scalable backend architecture

---

# 🚀 Future Enhancements

* 📍 Real-Time Train Tracking
* 📱 Mobile Application
* 🤖 AI-Based Fare Prediction
* 🌐 Multilingual Support
* 🎟️ Smart Card Integration
* 📊 Analytics Dashboard

---

# 📂 Project Structure

```bash
Metro-Management-System/
│
├── frontend/
│   ├── HTML
│   ├── CSS
│   └── JavaScript
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── database/
│   └── SQL files
│
└── README.md
```

---

# 🧠 Concepts Used

* Full Stack Development
* REST APIs
* Relational Database Management
* Authentication & Authorization
* Payment Gateway Integration
* CRUD Operations
* SQL Joins and Relationships

---

# 📸 Screenshots

Add your project screenshots here:

* Login Page
* User Dashboard
* Ticket Booking Page
* Payment Gateway
* Admin Dashboard
* Metro Line Management
* Schedule Management

Example:

```md
![Login Page](screenshots/login.png)
```

---

# ▶️ How to Run the Project

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Metro-Management-System.git
```

---

## 2️⃣ Install Dependencies

### Backend

```bash
cd backend
npm install
```

---

## 3️⃣ Setup MySQL Database

* Create a MySQL database
* Import SQL schema
* Update database credentials in configuration file

---

## 4️⃣ Run Backend Server

```bash
npm start
```

or

```bash
nodemon server.js
```

---

## 5️⃣ Run Frontend

Open the frontend using Live Server or directly open `index.html`.

---

# 👩‍💻 Team Members

* Swara Saoji
* Vidhi Patel
* Ishita Rane

---

# 📚 References

* [MySQL Documentation](https://dev.mysql.com/doc/?utm_source=chatgpt.com)
* [Node.js Documentation](https://nodejs.org/docs/latest/api/?utm_source=chatgpt.com)
* [Express.js Documentation](https://expressjs.com/?utm_source=chatgpt.com)
* [MDN Web Docs](https://developer.mozilla.org/en-US/?utm_source=chatgpt.com)
* [Razorpay Documentation](https://razorpay.com/docs/?utm_source=chatgpt.com)
* [Pune Metro Official Website](https://www.punemetrorail.org/?utm_source=chatgpt.com)

---

# ⭐ Conclusion

The Metro Management System successfully demonstrates the implementation of a real-world transportation management solution using full-stack technologies and database management concepts. The project improves operational efficiency, reduces manual effort, and provides a scalable foundation for future metro automation systems.
