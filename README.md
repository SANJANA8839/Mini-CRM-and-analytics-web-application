🚀 Tech Stack

Frontend: React, TailwindCSS, Axios, Recharts, Vite
Backend: FastAPI, Uvicorn, SQLAlchemy, Pydantic
Database: SQLite
Environment: Python Virtual Environment (venv), Node.js

⚙️ Features

🔐 User Authentication – Secure login and registration system.

👥 Customer Management – Add, edit, delete, and view customer records.

💼 Deal Tracking – Manage sales deals and link them to customer data.

📊 Analytics Dashboard – Visualize insights using interactive charts (Recharts).

📁 CSV Import/Export – Easily manage large data using file operations.

⚡ Real-Time Updates – Fast API responses and smooth UI interaction.

🧠 Project Structure
Mini-CRM-Analytics-Web-App/
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── routes/
│   │   ├── models/
│   │   ├── schemas/
│   │   └── database.py
│   ├── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── README.md

🧩 Setup & Run Instructions
🔹 Step 1: Clone Repository
git clone https://github.com/yourusername/Mini-CRM-Analytics-Web-App.git
cd Mini-CRM-Analytics-Web-App

🔹 Step 2: Setup Backend
cd backend
python -m venv venv
venv\Scripts\activate     # On Windows
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000


👉 Backend will run at: http://127.0.0.1:8000

🔹 Step 3: Setup Frontend
cd ../frontend
npm install
npm run dev


👉 Frontend will run at: http://localhost:5173

📈 Screenshots

Add screenshots or demo GIFs here (like login page, dashboard, analytics view, etc.)

💡 Future Improvements

Add role-based user access (Admin/User)

Integrate cloud database (PostgreSQL)
