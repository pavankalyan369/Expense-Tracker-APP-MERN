# Expense Tracker WebApp (MERN Stack)

A fully-featured, responsive Expense Tracker Web Application that allows users to track and categorize their daily income and expenses efficiently. Built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) with modern UI via **Tailwind CSS**.

---

## Problem Statement

Managing daily expenses and incomes can become overwhelming without a structured and accessible tracking system. Many people struggle to maintain budgets, categorize expenses, and visualize financial data. This project simplifies the financial management process by providing a user-friendly, full-stack solution to track and manage expenses securely and visually.

---

## Objectives

* Add, edit, and delete income or expense records.
* Categorize transactions with custom or preset tags.
* Store user data securely in a MongoDB database.
* Visualize financial statistics with graphs and summaries.
* Deploy a responsive app accessible across devices.

---

## Tech Stack

| Tool/Tech        | Purpose                                 |
| ---------------- | --------------------------------------- |
| **MongoDB**      | NoSQL database for storing transactions |
| **Express.js**   | Backend web framework for API logic     |
| **React.js**     | Frontend JavaScript library for UI      |
| **Node.js**      | Backend runtime environment             |
| **Tailwind CSS** | Styling and responsive layout           |
| **Netlify**      | Frontend deployment                     |

---

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/ihtasham42/Expense-Tracker-Mern.git
```

### 2. Install Backend Dependencies

```bash
cd Expense-Tracker-Mern
npm install
```

### 3. Install Frontend Dependencies

```bash
cd client
npm install
```

### 4. Environment Setup

Create a `.env` file in the root directory with the following:

```env
MONGO_URI=<your_mongo_uri>
PORT=5000
```

> You can get your MongoDB URI by creating a free cluster on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

---

## Running the Project Locally

### Start Backend Server

```bash
npm run server
```

### Start Frontend React App

```bash
cd client
npm start
```

Now, navigate to: [http://localhost:3000](http://localhost:3000)

---

## Interface Snapshots

### Dashboard UI

<img src="screenshots/e1.png" width="600"/>

### Add Transaction Form

<img src="screenshots/e2.png" width="600"/>

### Analytics and Charts

<img src="screenshots/e3.png" width="600"/>

> *These screenshots visually summarize the key features and interface of the application.*

---

## Features Overview

* **Add/Edit/Delete Transactions**: Manage financial records easily.
* **Categorization**: Transactions organized with category filters.
* **Statistics Dashboard**: View total income, expense, and savings.
* **Data Visualization**: Beautiful pie/bar charts powered by `chart.js`.
* **Responsive Design**: Optimized for desktop and mobile.
* **Secure Backend**: Built with Express and connected to MongoDB.

---

## Project Structure

```bash
Expense-Tracker-Mern/
│
├── client/                  # React Frontend
│   ├── public/
│   └── src/
│       ├── components/      # Reusable UI Components
│       ├── pages/           # Routes & Pages
│       └── App.js           # Root Component
│
├── config/
│   └── db.js                # MongoDB connection setup
│
├── models/
│   └── Transaction.js       # Mongoose schema
│
├── routes/
│   └── transactionRoutes.js # REST API Routes
│
├── controllers/
│   └── transactionController.js # Route handlers
│
├── .env                     # Environment variables
├── server.js                # Entry point for backend
└── package.json
```

---

## Future Improvements

* Cloud storage integration for exporting data
* PWA (Progressive Web App) support
* Monthly/yearly financial insights

---


