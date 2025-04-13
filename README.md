# Store Rating Management Application
🛒 Store Rating Platform (Full-Stack Web App)
A role-based web application where users can register, browse stores, and submit ratings (1–5). Store owners can view ratings given to their store, and system administrators can manage users, stores, and see platform stats via a dashboard.

Key Features:

Role-based access: Admin, Normal User, Store Owner

Store listing, rating & review system

Admin dashboard with user/store/rating management

Secure login/signup with validation

Tech Stack: React.js, Express.js, PostgreSQL/MySQL

🧰 Tech Stack
Frontend: React.js + Tailwind CSS

Backend: Express.js (Node.js)

Database: PostgreSQL / MySQL

Authentication: Basic login system (extensible to JWT)

API Communication: RESTful APIs using Axios

Validation: Custom validations on form inputs

📦 Functional Modules
Authentication & Authorization

Login & Signup with validation

Role-based route handling

Store Management

Add/view stores

Store listing with average & personal ratings

Rating System

One user, one rating per store (editable)

Rating validation between 1 and 5

Admin Dashboard

Platform statistics (user, store, rating count)

User and store management with search & filters

Store Owner Dashboard

View customer ratings and calculate average



**Output Images**
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073307.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073332.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073346.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073355.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073407.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073416.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073446.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073630.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073644.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073654.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073704.png)
![Image Alt](https://github.com/manish-87/Store-Rating-Management/blob/main/Screenshot%202025-03-15%20073711.png)

## 🚀 Overview
A web application that enables users to submit and manage ratings for stores registered on the platform. It features role-based access for different types of users.

## 🛠️ Technology Stack

- **Backend**: ExpressJs / Loopback / NestJs (Choose one)
- **Database**: PostgreSQL / MySQL
- **Frontend**: ReactJs

## 🎯 Functional Requirements

### 🌟 User Roles

- **System Administrator**
- **Normal User**
- **Store Owner**

---

## 🔐 Single Authentication System
- A unified login and registration system for all users.

## 🔑 User Roles & Functionalities

### **System Administrator**
- Add new stores, normal users, and admin users.
- Dashboard displaying:
  - Total number of users
  - Total number of stores
  - Total number of submitted ratings
- Manage users (create, list, filter, view details).
- Manage stores (list with details).
- Logout functionality.

### **Normal User**
- Signup and login functionality.
- View and search store listings by name or address.
- Submit and modify store ratings (1-5).
- Update their password after login.
- Logout functionality.

### **Store Owner**
- Login and update their password.
- Dashboard to view:
  - List of users who rated their store.
  - Average rating of their store.
- Logout functionality.

## ✔️ Form Validations
- **Name**: Min 20 characters, Max 60 characters
- **Address**: Max 400 characters
- **Password**: 8-16 characters, at least one uppercase letter, one special character
- **Email**: Standard email format validation

## 🔍 Additional Features
- Sorting (ascending/descending) in tables by fields like Name, Email, etc.
- Clean and best-practice-oriented database schema.

## 🚀 Getting Started

### **1. Backend Setup**

Navigate to your backend directory:

```sh
cd server
npm install
```

Configure your database connection in `.env` file:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/your-database-name
```

Then start backend:

```sh
npm run dev
```

Backend runs at `http://localhost:3000`

For using super admin use these 

```
admin@example.com
Admin123!
```

## ⚠️ **Important**
- Ensure PostgreSQL/MySQL is running.
- Create your database clearly and set connection URL in your backend `.env` clearly.

Example `.env`:
```env
DATABASE_URL=postgresql://postgres:yourpassword@localhost:5432/your-database-name
```

---




## 📬 Contributing

Feel free to contribute or raise issues through pull requests.

## 📝 License

Specify clearly here if needed (MIT, etc.)

---

Made with ❤️ by [Manish](https://github.com/manish-87)
```

