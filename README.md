
# 🚆 Train Booking System (Java)

> A console-based Java project simulating a train reservation system with user booking, ticket generation, and local JSON storage.

---

## 📌 About

This project is a **Java-based Train Booking System** designed to simulate train searching, booking, and ticket management.

It uses:

- **Pure Java (OOP concepts)**
- **Modular project structure**
- **Local JSON files as a mock database**
- **Service-based architecture**

Perfect for academic submissions, learning core Java, OOP, file handling, and service-driven development.

---

## 🚀 Features

- 🔍 Search trains  
- 🎫 Book tickets  
- 👤 Manage users  
- 🗂 Local JSON DB for storing user and train data  
- 🧩 Clean modular Java architecture  
- 📄 Ticket object generation  
- 🧪 Easy to extend (add cancellation, payment, etc.)

---

## 🌈 Tech Stack

| Technology | Description |
|-----------|-------------|
| ☕ Java | Programming language |
| 📁 JSON | Local DB storage |
| 🧰 OOP Architecture | Clean modular design |
| 📦 Gradle | Build automation |

---

## 📁 Project Structure

```
src/
 └── main/java/org/example/
      ├── Services/
      │     ├── TrainService.java
      │     └── UserBookingService.java
      │
      ├── entities/
      │     ├── Ticket.java
      │     ├── Train.java
      │     └── User.java
      │
      ├── localDb/
      │     ├── trains.json
      │     └── users.json
      │
      ├── util/
      │     └── UserServiceUtil.java
      │
      └── App.java
```

---

## 🧠 Module Breakdown

### **Services/**
Business logic layer:

- `TrainService.java` → train searching, listing  
- `UserBookingService.java` → handles ticket booking  

### **entities/**
Object models:

- `Train.java` → train details  
- `User.java` → user details  
- `Ticket.java` → generated ticket info  

### **localDb/**
Local mock database:

- `trains.json` → train records  
- `users.json` → user records  

### **util/**
Utility functions reused across the system.

### **App.java**
The main entry point of the entire application.

---

## ▶️ Running the Project

### 1️⃣ Clone the repo

```
git clone https://github.com/<your-username>/TrainBookingSystem.git
cd TrainBookingSystem
```

### 2️⃣ Run the project

```
gradlew run
```

or compile manually:

```
javac App.java
java App
```

---

## 📄 Sample Train JSON (localDb/trains.json)

```json
[
  {
    "trainId": 101,
    "trainName": "Rajdhani Express",
    "source": "Delhi",
    "destination": "Mumbai",
    "seats": 50
  }
]
```

---

## ⭐ What This Project Is Demonstrates

- Great for Java OOP practice  
- Demonstrates file handling (JSON read/write)  
- Clean layered architecture  
- Beginner-friendly yet extendable  
- Ideal GitHub project for resumes  

---

## 👨‍💻 Author

**Anurag Upadhyay**  
GitHub: https://github.com/Uanuragdhyay

