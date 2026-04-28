
# 💰 Unanomsa – Personal Budgeting Application

## 📱 Overview

Unanomsa is a personal budgeting Android application designed to help users effectively manage their finances. The application allows users to track expenses, organise spending into categories, and set monthly budget goals. Users can also attach optional images to expense entries for better record-keeping.

The app is built using modern Android development practices and follows the MVVM (Model-View-ViewModel) architecture to ensure scalability, maintainability, and clean code structure.

---

## ✨ Features

### 🔐 User Authentication

* Secure login system using username and password
* Session-based access for returning users

### 📂 Category Management

* Create custom categories for expenses (e.g. Food, Transport, Rent)
* Helps users organise financial data efficiently

### 💸 Expense Tracking

Users can log detailed expenses including:

* Date of transaction
* Start and end time
* Description of expense
* Linked category
* Optional image attachment (receipts or proof)

### 🎯 Budget Goals

* Set minimum and maximum monthly budget limits
* Track spending behaviour against financial targets

---

## 🛠 Technologies Used

* Kotlin (Android development language)
* Android SDK
* Room Persistence Library (local database)
* MVVM Architecture (ViewModel + LiveData)
* RecyclerView (lists and data display)
* Glide / Picasso (image loading)

---

## 🏗 Architecture

The application follows the MVVM architecture:

* **Model:** Room database entities and data layer
* **View:** Activities and UI components
* **ViewModel:** Handles logic and data communication between UI and database

This structure improves code readability, maintainability, and separation of concerns.

---

## 🚀 Installation & Setup

### Prerequisites

* Android Studio installed
* Android SDK configured
* Basic understanding of Kotlin

### Steps

1. Clone the repository:

```bash
git clone https://github.com/yourusername/unanomsa-app.git
```

2. Open the project in Android Studio
3. Allow Gradle to sync dependencies
4. Run the application on an emulator or physical device

---

## 📖 How to Use

1. Open the app
2. Register or log in
3. Create expense categories
4. Add expenses with details (date, time, description, category)
5. Optionally upload images for receipts
6. Set monthly budget limits
7. Monitor your spending habits

---

## 🎥 Video Demonstration

A full walkthrough of the application is available here:
[https://www.youtube.com/@crystalex9717](https://youtu.be/ofFh7fSsWgM?feature=shared)

---

## 📌 Future Improvements

* Cloud backup using Firebase
* Financial analytics dashboard
* Monthly PDF reports
* Dark mode support
* Budget warning notifications
* AI-based spending insights

---

## 📚 References (Harvard Style)

Independent Institute of Education (IIE) (2024) *Harvard Style Reference Guide – Adapted for The IIE*. Rosebank College. Available at: [https://www.rosebankcollege.co.za](https://www.rosebankcollege.co.za) (Accessed: 28 April 2026). ([Studocu][1])


