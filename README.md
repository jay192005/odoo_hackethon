# ExpenseFlow 🚀

> A next-generation Reimbursement & Expense Management System, built for the Odoo Hackathon.

ExpenseFlow simplifies the chaotic process of managing team expenses by introducing a sleek, intuitive, and highly responsive platform. Say goodbye to messy email threads and lost receipts. ExpenseFlow brings real-time status tracking, robust multi-tier approval workflows, and centralized team expense dashboards—all under one beautifully designed UI. 

Designed with human experience in mind, ExpenseFlow aims to make submitting, reviewing, and tracking expenses as painless as possible.

---

## ✨ Features

- **Dynamic Role-based Dashboards:** Tailored user experiences for Employees, Managers, and Admins.
- **Smart Receipt Management:** Supports drag-and-drop file uploads (Images & PDFs) with dynamic previewing and intuitive inline viewer.
- **Multi-Level Approval Workflow:** Hardcoded security ensures an expense passes through Manager approval before moving to the Admin queue for ultimate sign-off.
- **Micro-interactions & UX:** Crafted using Tailwind CSS, glassmorphic touches, and smooth transitions that bring the interface to life.
- **Automated Rejection Transparency:** When a manager or admin rejects an expense, a clear, red-highlighted reason is visibly displayed right on the submitter's dashboard.

---

## 🛠 Tech Stack

**Frontend Framework:** React + Vite
**Language:** TypeScript
**Styling Ecosystem:** Tailwind CSS, PostCSS, Google Fonts (Inter)
**Icons:** Lucide React
**Routing & Navigation:** React Router
**Backend Engine:** Flask (Python)
**Database Mapping:** MySQL + PyMySQL DB adapter
**Authentication:** Context-backed JWT flows

---

## 🚀 Getting Started

### 1. Requirements
Ensure you have the following installed on your machine:
- Node.js (v18+)
- Python (v3.10+)
- MySQL Server

### 2. Database Setup
1. Create a MySQL database named `odoo_hack`.
2. Seed the database tables by utilizing the mock architecture in the `/backend` folder.
3. Configure your local `.env` variables using `backend/.env.example` as a template.

### 3. Running the API Backend
Open your terminal and navigate to the `backend/` directory:

```bash
cd backend
pip install -r requirements.txt
python app.py
```

The Flask API will start running on port `5000`.

### 4. Running the Frontend Portal
In a new terminal, navigate to the `frontend/` directory:

```bash
cd frontend
npm install
npm run dev
```

The app will be served via Vite (usually on port `5173`). Have fun exploring the portals!

---

## 👨‍💻 Developed For
**Odoo Hackathon Submission**
*Built with ❤️ by Hackathon Team*
