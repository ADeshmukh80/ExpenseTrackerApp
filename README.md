# 💸 Expense Management System

A full-stack web application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) to help users effectively track, manage, and analyze their expenses. Designed with a clean, responsive UI and packed with insightful visual reports, this tool serves both individuals and organizations for better financial planning.

---

## 📌 Project Overview

This Expense Management System allows users to:

- Log daily expenses
- Organize them by categories
- Analyze spending patterns through visual reports
- Manage access through secure authentication and roles

---

## 🎯 Objectives

- **Simplify Expense Tracking** – Seamlessly log daily transactions
- **Gain Financial Insights** – Use visual reports and analytics
- **CRUD Operations** – Create, Read, Update, Delete expenses & categories
- **Custom Reporting** – Filter reports by custom date ranges and categories

---

## 🚀 Features

### 🔐 Authentication & Authorization

- **User Authentication** – Secure registration and login
- **Role-Based Access** – Admin and regular user roles
- **JWT Integration** – Secure token-based authentication

### 🧾 Expense & Category Management

- Add, edit, and delete expenses with date, category, and description
- Manage custom categories
- Attach receipts/documents to expense entries (optional)

### 📊 Dashboard & Reporting

- Overview Dashboard: Recent transactions, totals, and category breakdown
- Visual Reports: Pie charts and bar graphs
- Custom Reports: Filter data by date and category

### 📱 Responsive UI

- Fully responsive on desktop, tablet, and mobile
- Built with **React.js**, **Bootstrap**, and **Material Icons**
- Dynamic visuals using `tsparticles`

---

## 🏗 Technical Architecture

### 🖥 Frontend

- **Framework**: React.js
- **Libraries Used**:
  - `react-bootstrap` – UI components
  - `tsparticles` – Animated backgrounds
  - `react-datepicker` & `moment` – Date handling
  - `unique-names-generator` – Name generation

### 🌐 Backend

- **Runtime**: Node.js with Express.js
- **API Architecture**: RESTful endpoints
- **Security**: JWT authentication & middleware-protected routes

### 🗂 Database

- **Database**: MongoDB
- **ORM**: Mongoose – Schema modeling, validation, and querying

---

## 🛠 Run Locally

### Step 1: Clone the Repository

```bash
git clone https://github.com/ADeshmukh80/ExpenseTrackerApp.git
cd ExpenseTrackerApp
