# 🏥 Patient Management System (Spring Boot + React)

A **full-stack Hospital Management System** built using Spring Boot and React.
This application helps hospitals manage patients, appointments, and medical records in a digital and efficient way.

---

# 🎯 Project Overview

## ❓ Problem

In many hospitals:

* Patient records are maintained manually
* Appointment scheduling is not organized
* Data is scattered across files and registers
* Managing patient history is difficult

👉 This leads to:

* Time consumption
* Data inconsistency
* Poor patient experience

---

## 🎯 Aim

To build a **digital hospital management system** that:

* Stores patient records securely
* Manages appointments efficiently
* Provides CRUD operations for hospital data
* Improves hospital workflow

---

## ✅ Solution

This system provides:

* 👤 Patient Registration & Management
* 📋 View Patient Details
* ✏️ Update Patient Information
* ❌ Delete Patient Records
* 📅 Appointment handling (optional extension)
* 🔄 REST API communication between frontend and backend

---

# 🛠️ Technologies Used

### Backend

* Spring Boot 3.4.2
* REST API (GET, POST, PUT, DELETE, PATCH)
* JPA & Hibernate
* DTO Pattern
* ModelMapper
* Oracle Database 23g

### Frontend

* React.js
* Bootstrap 4
* React Datepicker
* Material UI Components

---

# 📚 Important Libraries / References

* Date Picker: https://reactdatepicker.com/
* Checkbox Component: https://www.npmjs.com/package/@material/react-checkbox

---

# ⚙️ Requirements

To run this project, you need:

* ☕ JDK 23
* 📦 Maven 3+
* 🗄️ Oracle Database 23g
* 🟢 Node.js + npm

---

# 🚀 Running the Application Locally

---

## 🔹 Backend Setup (Spring Boot)

You can run the backend in two ways:

### ▶️ Option 1: Using IDE

Run the main class:

```
com.example.demo.FirstAppApplication
```

---

### ▶️ Option 2: Using Maven

```shell
mvn clean spring-boot:run
```

👉 Backend will run on:

```
http://localhost:8080
```

---

## 🔹 Frontend Setup (React)

### 📌 Steps

1. Clone the repository:

```shell
git clone <your-repo-url>
cd frontend
```

---

2. Install dependencies:

```shell
npm install
```

---

3. Run the application:

```shell
npm start
```

---

4. Open in browser:

```
http://localhost:3000
```

---

# ⚠️ Common Issues

* ❌ Database connection error → check Oracle credentials
* ❌ Port already in use → change backend port
* ❌ API not working → ensure backend is running
* ❌ Node errors → update Node.js version

---

# 📈 Future Improvements

* 📅 Advanced appointment scheduling system
* 🔐 Authentication & Role-based access
* 📊 Dashboard with analytics
* 📧 Email/SMS notifications
* ☁️ Cloud deployment (AWS / Azure)

---

# 🤝 Contribution

Contributions are welcome!

### Steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to branch
5. Open Pull Request

Author

---

# ⭐ Support

If you like this project, please give it a ⭐ on GitHub.
