# Daily Expense Tracker System

The **Daily Expense Tracker System** is a web-based application designed to help users efficiently manage their daily expenses. This application allows users to record and categorize their expenses, view detailed summaries, and analyze spending habits over time.

---

## 🚀 Features
- **User Registration and Login**: Secure authentication for personalized expense tracking.
- **Expense Recording**: Add, edit, or delete expenses with details like amount, category, and description.
- **Category Management**: Use default or custom categories for classifying expenses.
- **Expense Overview**: Generate daily, weekly, monthly, yearly summaries with visual insights.

---

## 📌 Objectives
The primary goal is to provide an intuitive platform for users to monitor their financial activities and improve budget management.

---

## 🎯 Functional and Non-Functional Requirements

### Functional
- User authentication.
- CRUD operations for expenses and categories.
- Summary generation with breakdowns by category and time period.

### Non-Functional
- **Usability**: User-friendly interface.
- **Performance**: Optimized for fast load times.
- **Scalability**: Supports multiple users and growing data.
- **Security**: Ensures encrypted storage for sensitive data.

---

## 👤 Target Users
This system is ideal for individuals, families, and professionals who want a simple yet powerful tool to track and manage daily expenses.

---

## 🌟 Novelty
- Customizable categories tailored to individual users' needs.
- Visualized expense summaries for enhanced understanding of financial habits.

---

## 🛠 Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP
- **Database**: MySQL

---

## 🛡 APIs Designed
1. **Authentication API**: User login, registration, and logout.
2. **Expense Management API**: Add, update, delete, and retrieve expenses.
3. **Category Management API**: CRUD operations for categories.
4. **Summary API**: Generate expense summaries by time periods.

---

## 🗂 Database Schema

### Tables
#### `users`
- `id` (Primary Key)
- `name`
- `email`
- `password` (hashed)

#### `expenses`
- `id` (Primary Key)
- `user_id` (Foreign Key from `users`)
- `amount`
- `category` 
- `description`
- `date`
- `created_at`
  

---

## 📐 High-Level System Design
1. **User Management Module**: Handles registration, authentication, and profile data.
2. **Expense Tracker Module**: Logs and manages expenses with category integration.


