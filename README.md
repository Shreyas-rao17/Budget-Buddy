# 💰 Budget Buddy

**Budget Buddy** is a simple personal finance tracker that lets users log transactions, set budgets, and track their expenses.

---

## 🔧 Tech Stack

- **Frontend:** Next.js (React)
- **Backend:** Node.js + Express
- **Database:** MySQL
- **Other Tools:** Chart.js, tailwind css

---

## 🚀 Features

- Add and view income/expense transactions
- Categorize spending
- Set monthly budgets
- Track remaining balance
- Set Goals and monitor progress towards it

---

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/budget-buddy.git
   cd budget-buddy
   ```

2. **Set up environment variables**

   Create a `.env` file in the both frontend and backend directories with your database credentials:

   ```
   DB_HOST=localhost
   DB_USER=your_mysql_user
   DB_PASSWORD=your_mysql_password
   DB_NAME=budget_buddy
   ```

3. **Install dependencies**
   ```bash
   # For frontend
   cd frontend
   npm install

   # For backend
   cd ../backend
   npm install
   ```

4. **Start the app**

   - Run backend:
     ```bash
     cd backend
     npm start
     ```

   - Run frontend:
     ```bash
     cd ../frontend
     npm run dev
     ```

   App runs at `http://localhost:3000`

---

## 🗃️ Database Schema (MySQL)

Basic schema includes tables for:

- `users`
- `transactions` (income/expenses)
- `categories`
- `budgets`
- `goals`
- `userCategories`
- `paymentMethods`
- `payments`

---

## 📂 Project Structure

```
budget-buddy/
├── backed/         # Next.js frontend
├── frontend/         # Express backend            
└── README.md
```

---
