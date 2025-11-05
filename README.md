# 🧩 Mini CRM & Analytics Web Application  

A full-stack **Customer Relationship Management (CRM)** web application that helps manage customers, deals, and sales analytics with a clean UI and real-time data updates.  

---

## 🚀 Tech Stack  

**Frontend:** React, Vite, Tailwind CSS, Axios, Recharts  
**Backend:** FastAPI, Uvicorn, SQLAlchemy, Pydantic  
**Database:** SQLite  
**Environment:** Python (venv), Node.js  

---

## ⚙️ Features  

- 🔐 **User Authentication** – Secure user login and registration system.  
- 👥 **Customer Management** – Create, update, delete, and view customer records.  
- 💼 **Deal Tracking** – Manage and monitor customer deals efficiently.  
- 📊 **Analytics Dashboard** – Interactive charts for visualizing key metrics.  
- 📁 **Data Handling** – Import/export customer data through CSV files.  
- ⚡ **Real-Time Updates** – Smooth interaction between frontend and backend.  

---

## ⚡ Setup & Run Instructions  

### 🧩 Step 1: Clone the Repository  
```bash
git clone https://github.com/yourusername/Mini-CRM-Analytics-Web-App.git
cd Mini-CRM-Analytics-Web-App
🧩 Step 2: Setup Backend (FastAPI)
bash
Copy code
cd backend
python -m venv venv
venv\Scripts\activate     # For Windows
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
➡ Backend runs on: http://127.0.0.1:8000

🧩 Step 3: Setup Frontend (React + Vite)
bash
Copy code
cd ../frontend
npm install
npm run dev
➡ Frontend runs on: http://localhost:5173
```


💡 Future Enhancements
🔑 Role-based user access (Admin/User)

☁️ Cloud database integration (PostgreSQL)

🐳 Docker containerization
