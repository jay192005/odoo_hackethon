# 🚀 ExpenseFlow

**A smart, simple, and beautiful Reimbursement Management System built for the Odoo Hackathon.**

Managing team expenses is usually a headache full of messy email threads, lost paper receipts, and slow payouts. **ExpenseFlow** fixes this. We built a fast, modern web platform that makes submitting, reviewing, and tracking expenses completely painless for everyone involved.

## ✨ Why ExpenseFlow? (Key Features)

* **👥 Three Dedicated Dashboards:** Custom, easy-to-use screens designed specifically for Employees (submitters), Managers (reviewers), and Admins (final decision-makers).
* **🧾 Smart Receipt Uploads:** Just drag and drop! Upload receipt images or PDFs and view them directly inside the app without needing to download them.
* **✅ Multi-Step Approval Engine:** Built-in security rules ensure an expense goes to the direct Manager first, and only moves to the Admin for final payout after the manager approves it.
* **💬 Clear Communication:** If an expense is rejected, the manager must provide a reason. This reason is highlighted in red directly on the employee's dashboard so there is no confusion.
* **🎨 Beautiful Experience:** Built with a focus on human experience. Expect smooth animations, modern glassmorphic designs, and instant loading times.

## 🛠 Our Tech Stack

**Frontend:**
* **Framework:** React + Vite (Using TypeScript)
* **Styling:** Tailwind CSS (Modern, responsive UI)
* **Icons & Fonts:** Lucide React & Google Fonts (Inter)
* **Routing:** React Router

**Backend:**
* **Engine:** Python with Flask 
* **Database:** MySQL (Connected via PyMySQL)
* **Security:** JWT (JSON Web Tokens) for safe, encrypted logins

---

## 🏁 How to Run the Project Locally

Follow these simple steps to get the project running on your own computer.

### 1. What You Need Installed
Make sure you have these downloaded and installed:
* [Node.js](https://nodejs.org/) (v18 or higher)
* [Python](https://www.python.org/downloads/) (v3.10 or higher)
* MySQL Server

### 2. Database Setup
1. Open your MySQL client and create a new database named: `odoo_hack`
2. Look inside the `backend/` folder for the database schema/mock data to set up your tables.
3. In the `backend/` folder, find the `.env.example` file. Copy it, rename the copy to `.env`, and fill in your local MySQL password and details.

### 3. Start the Backend (API)
Open your terminal and run these commands to start the Python server:

    cd backend
    pip install -r requirements.txt
    python app.py

*The API will now be running on `http://localhost:5000`*

### 4. Start the Frontend (Website)
Open a **new** terminal window and run these commands to start the React app:

    cd frontend
    npm install
    npm run dev

*The website will now be running on `http://localhost:5173`. Click the link in your terminal to open it in your browser and explore ExpenseFlow!*
