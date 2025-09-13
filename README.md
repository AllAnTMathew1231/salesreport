
````markdown
# SalesReport 📊

A full-stack web application for **sales reporting and management**.  
It provides interactive dashboards, charts, and order management features to help businesses analyze and manage their sales data effectively.

---

## 🚀 Features

- User authentication & authorization (JWT-based)  
- Sales & purchase order management  
- Interactive dashboards with charts and reports  
- Role-based views (salespeople, vendors, admins)  
- Vendor performance and profit analysis  
- Modular frontend and backend architecture  

---

## 🛠️ Tech Stack

- **Frontend**: React + Vite + TypeScript, TailwindCSS  
- **Backend**: Node.js + Express + TypeScript  
- **Database**: MongoDB (Mongoose)  
- **Others**: JWT, ESLint, PostCSS  

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
    ├── package.json        # Backend dependencies
    └── .env.example        # Env variables template
````

---

## ⚙️ Setup & Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/AllAnTMathew1231/salesreport.git
cd salesreport
```

### 2️⃣ Install Dependencies

Frontend:

```bash
npm install
```

Backend:

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

Backend (API):

```bash
cd server
npm run dev
```

Frontend (React app):

```bash
npm run dev
```

* Frontend: `http://localhost:5173`
* Backend: `http://localhost:5000`

---

## 📊 Usage

1. Start both backend and frontend
2. Open `http://localhost:5173` in your browser
3. Sign up or log in
4. Manage sales/purchase orders and view dashboards

---

## 🤝 Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m "feat: add new feature"`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---


# Demo Account Logins

# PURCHASE ACCOUNT

Username
```bash
purchase101@company.com
````
Password

```bash
purchase@company.com
```

# SALES ACCOUNT

Username

```bash
sales101@company.com
```
Password

```bash
sales@company.com
```

# VENDOR ACCOUNT

Username

```bash
vendor101@company.com
```
Password
```bash
vendor@company.com
```
---


## 📜 License

MIT License © 2025 [AllAnTMathew1231](https://github.com/AllAnTMathew1231)

---

## 📬 Contact

* GitHub: [AllAnTMathew1231](https://github.com/AllAnTMathew1231)
* Email: **[ajmallan123l@gmail.com](mailto:ajmallan123l@gmail.com)**

```




