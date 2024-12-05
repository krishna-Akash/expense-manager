# Daily Expense Tracker System

The **Daily Expense Tracker System** is a web-based application designed to help users efficiently manage their daily expenses. This application allows users to record and categorize their expenses, view detailed summaries, and analyze spending habits over time.

---

## 🚀 Features
- **User Registration and Login**: Secure authentication for personalized expense tracking.
- **Expense Recording**: Add, edit, or delete expenses with details like amount, category, and description.
- **Category Management**: Use default or custom categories for classifying expenses.
- **Expense Overview**: Generate daily, weekly, monthly, yearly summaries with visual insights.
- **Report Generation**: Generate reports and recieve it via email using smtp.

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

---

## Screenshots


![Screenshot 2024-11-14 143256](https://github.com/user-attachments/assets/b36890bb-3d95-4614-b7cc-cb8b6f177eee)
![Screenshot 2024-11-14 143316](https://github.com/user-attachments/assets/e159a870-2f0f-4410-91d0-7b7efe6a5a5c)
![Screenshot 2024-11-14 143127](https://github.com/user-attachments/assets/bb506438-cbcf-49a0-9b6f-6e02608c6149)
![Screenshot 2024-11-14 143017](https://github.com/user-attachments/assets/696d3673-673d-43db-bf40-15693020489d)
![Screenshot 2024-11-14 142934](https://github.com/user-attachments/assets/2cafe672-be70-4d75-adc7-fd9b74c5b1f5)
![Screenshot 2024-11-14 142857](https://github.com/user-attachments/assets/807e2a9d-ef8a-46f3-98cf-4c67d3db3a03)
![Screenshot 2024-11-14 142813](https://github.com/user-attachments/assets/a9164a2e-3dfb-46f8-933b-490d6166237f)
![Screenshot 2024-11-14 142727](https://github.com/user-attachments/assets/111b7804-25cc-491f-b779-919add149f9b)
![Screenshot 2024-11-14 142219](https://github.com/user-attachments/assets/6e686fe4-160e-4fce-addf-c8366cec7b83)
![Screenshot 2024-11-14 142134](https://github.com/user-attachments/assets/0985da8b-9a3b-4ad3-829b-4087f7e38425)
![Screenshot 2024-11-14 141458](https://github.com/user-attachments/assets/50155eb0-140a-4849-ae72-ec295d797532)
![Screenshot 2024-11-14 143633](https://github.com/user-attachments/assets/461ff08b-b539-479f-89d2-587efef4f171)
![Screenshot 2024-11-14 143606](https://github.com/user-attachments/assets/ba8a5af0-b454-4cc6-8624-4b19e64c61de)
![Screenshot 2024-11-14 143530](https://github.com/user-attachments/assets/2516af51-ba97-4f00-a851-8d2e3d8eabfe)
