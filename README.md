# 🚆 IRCTC Train Booking System

A console-based Train Booking System inspired by the IRCTC platform, built to simulate real-world railway reservation operations such as ticket booking, cancellation, and passenger management.

---

## 📌 Project Overview

The IRCTC Train Booking System is designed to demonstrate core programming concepts including:

- Data structures
- Object-oriented programming
- User input handling
- Basic ticket management logic

This project simulates how railway reservation systems manage seat availability and passenger records.

---

## ✨ Features

- 🎟 Book Train Tickets
- ❌ Cancel Tickets
- 📋 View Booked Tickets
- 👤 Passenger Details Management
- 💺 Seat Availability Tracking
- 🔁 Waitlist Handling (if implemented)
- 🖥 Console-Based Interactive Menu

---

## 🛠 Tech Stack

- **Language:** Java  
- **Concepts Used:** OOP, Collections, Conditional Logic, Loops  
- **Execution Type:** Console Application  

---

## 📂 Project Structure

IRCTC-Train-Booking-System/
│
├── Main.java
├── Passenger.java
├── Ticket.java
├── Train.java
└── README.md

---

## ⚙️ How It Works

1. User selects an option from the menu:
   - Book Ticket
   - Cancel Ticket
   - View Bookings
   - Exit

2. System checks seat availability.

3. If seats are available:
   - Ticket is confirmed.
   - Passenger details are stored.

4. If seats are full:
   - Ticket moves to waiting list (if implemented).

5. On cancellation:
   - Seat is freed.
   - Waiting list passenger (if any) gets confirmed.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

git clone https://github.com/Rudraprasad2302/IRCTC-Train-Booking-System.git
cd IRCTC-Train-Booking-System

### 2️⃣ Compile Java Files

javac *.java

### 3️⃣ Run the Application

java Main

---
