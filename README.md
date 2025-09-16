
````markdown
# SalesFlow 📊

A full-stack web application for **sales reporting and management**.  
It provides interactive dashboards, charts, and order management features to help businesses analyze and manage their sales data effectively.

---

## 🚀 Features

-  User authentication & authorization (JWT-based)  
-  Sales & purchase order management  
-  Interactive dashboards with charts and reports  
-  Role-based views (Salesperson, Vendor, Admin/Purchase Dept)  
-  Vendor performance and profit analysis  
-  Modular frontend and backend architecture  
-  PDF invoice generation (dark/light themes)  
-  Dark mode as default, responsive mobile-first UI  

---

## 🛠️ Tech Stack

- **Frontend**: React + Vite + TypeScript, TailwindCSS, shadcn/ui, Framer Motion  
- **Backend**: Node.js + Express + TypeScript  
- **Database**: MongoDB (Mongoose ORM)  
- **Authentication**: JWT + bcrypt  
- **Charts**: Recharts  
- **PDF Export**: jsPDF or pdfmake  

---

## 📂 Project Structure

```plaintext
salesreport/
├── README.md
├── package.json            # Frontend dependencies
├── vite.config.ts
├── tsconfig.json
├── tailwind.config.js
├── postcss.config.js
├── src/                    # Frontend code
│   ├── components/         # UI components
│   ├── contexts/           # React contexts
│   ├── utils/              # Utility functions
│   ├── App.tsx
│   └── main.tsx
└── server/                 # Backend code
    ├── server.js           # Express entry point
    ├── routes/             # API routes
    ├── models/             # Database models
    ├── middleware/         # Auth middleware
    ├── utils/              # PDF generation, helpers
    ├── package.json        # Backend dependencies
    └── .env.example        # Env variables template
````

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/AllAnTMathew1231/salesreport.git
cd salesreport
```

### 2️⃣ Install Dependencies

**Frontend:**

```bash
npm install
```

**Backend:**

```bash
cd server
npm install
cd ..
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in `server/`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4️⃣ Run the Application

**Backend (API):**

```bash
cd server
npm run dev
```

**Frontend (React app):**

```bash
npm run dev
```

* Frontend: [http://localhost:5173](http://localhost:5173)
* Backend: [http://localhost:5000](http://localhost:5000)

---

## 📊 Usage

1. Start both backend and frontend
2. Open [http://localhost:5173](http://localhost:5173) in your browser
3. Sign up or log in
4. Manage sales/purchase orders and view analytics dashboards
5. Export invoices as PDF (dark/light theme option)
6. Update profile & avatar

---

## 📜 License

MIT License © 2025

---

## 👥 Contributors

* **Aavani Krishna**

  * ✉️ Email: [aavanikrishna85@gmail.com](mailto:aavanikrishna85@gmail.com)
  * 🐙 GitHub: [aavanikrishna](https://github.com/aavanikrishna)
  * 🔗 LinkedIn: [Aavani Krishna](https://www.linkedin.com/in/aavani-krishna-914893214)

* **Allan T Mathew**

  * ✉️ Email: [ajmallan123l@gmail.com](mailto:ajmallan123l@gmail.com)
  * 🐙 GitHub: [AllAnTMathew1231](https://github.com/AllAnTMathew1231)
  * 🔗 LinkedIn: [Allan T Mathew](https://www.linkedin.com/in/allantmathew/)

* **Amna Zaynab**

  * ✉️ Email: [amnazayn20@gmail.com](mailto:amnazayn20@gmail.com)
  * 🐙 GitHub: [amna-zaynab](https://github.com/amna-zaynab)
  * 🔗 LinkedIn: [Amna Zaynab](https://www.linkedin.com/in/amna-zaynab-195b2127a)

* **Denita Maria**

  * ✉️ Email: [denitamaria06@gmail.com](mailto:denitamaria06@gmail.com)
  * 🐙 GitHub: [DenitaMariaJM](https://github.com/DenitaMariaJM)
  * 🔗 LinkedIn: [Denita Maria](https://www.linkedin.com/in/denita-maria)

* **Faiza Nadeer**

  * ✉️ Email: [faizanadeer@gmail.com](mailto:faizanadeer@gmail.com)
  * 🐙 GitHub: [faizanadeer](https://github.com/faizanadeer)
  * 🔗 LinkedIn: [Faiza Fathima](http://linkedin.com/in/faiza-fathima-4a1b07342)






