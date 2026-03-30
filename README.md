# 🚀 Smart Elevator Control System

## 📌 Overview

This project implements a **Smart Elevator Control System in Java**, designed to simulate real-world elevator operations using strong **Object-Oriented Programming (OOP)** principles and the **State Design Pattern**.

The system dynamically manages elevator behavior such as movement, request handling, safety checks, and operational modes (normal, emergency, maintenance). It focuses on **clean architecture, modular design, and realistic simulation** rather than just basic functionality.

---

## 🏗️ Project Structure

```
src/
│
├── Main.java                # Entry point of the application
│
├── controller/             # Controls system flow and decision-making
│   └── ElevatorController.java
│
├── model/                  # Core data models
│   ├── Elevator.java
│   └── Request.java
│
├── state/                  # State Design Pattern implementation
│   ├── ElevatorState.java
│   ├── IdleState.java
│   ├── MovingUpState.java
│   ├── MovingDownState.java
│   ├── DoorOpenState.java
│   ├── EmergencyState.java
│   └── MaintenanceState.java
│
├── ui/                     # Console-based user interface
│   └── ConsoleUI.java
│
├── exception/              # Custom exception handling
│   ├── InvalidFloorException.java
│   └── OverloadException.java
│
├── docs/                   # Additional documentation
├── report/                 # Project report (PDF)
└── slides/                 # Presentation slides
```

---

## ⚙️ How to Run

1. Ensure **Java (JDK 8 or above)** is installed
2. Open terminal in project directory
3. Compile the project:

   ```
   javac -sourcepath src src/Main.java
   ```
4. Run the application:

   ```
   java -cp src Main
   ```

---

## ✨ Features

### 🚪 Core Functionalities

* Floor request handling (normal & priority)
* Dynamic elevator movement simulation (floor-by-floor)
* State-based behavior control

### ⚡ Safety Features

* Overload detection (prevents unsafe movement)
* Emergency mode (halts operations)
* Maintenance mode (disables system usage)

### 🧠 Smart Design

* State Design Pattern for dynamic behavior
* Priority queue-based request handling
* Input validation using custom exceptions

---

## 🧩 OOP Concepts Demonstrated

* **Abstraction** → `ElevatorState` interface
* **Encapsulation** → Private fields with getters/setters
* **Inheritance** → State classes implementing common behavior
* **Polymorphism** → Dynamic method execution based on state
* **Exception Handling** → Custom exceptions for invalid operations
* **Collections** → Queue-based request management
* **Threads** → Simulated movement using `Thread.sleep()`

---

## 🔄 System Workflow

1. User interacts via console menu
2. Inputs are validated
3. Requests are sent to the controller
4. Controller determines elevator direction
5. Elevator state handles movement and transitions
6. Safety checks (overload, emergency, maintenance) are enforced
7. System returns to menu for next action

---

## 📊 Documentation

* 📄 Project Report: [text](file:///C:/Users/Sandip%20Bhattacharyya/Desktop/OOPs%20Project.pdf)
* 🎥 Demo Video: <video controls src="Tech Company.mp4" title="Title"></video>
* 📐 UML Diagram: [text](<img width="1449" height="2632" alt="diagram-export-3-29-2026-10_28_17-PM" src="https://github.com/user-attachments/assets/33534547-3864-4458-89a1-e21c5c0a8684" />
)

---

## 📌 Key Highlights

* Clean **layered architecture**
* Proper use of **State Design Pattern**
* Strong **OOP implementation**
* Focus on **safety and realism**
* Maintainable and extensible codebase

---

## 👨‍💻 Author

**Sandipta Bhattacharyya**
B.Tech CSE (Cybersecurity, IoT & Blockchain)

---

## 📜 License

This project is developed for academic purposes.
