# 💰 Money Tracker App

A full-stack personal finance application that allows users to **track income and expenses in real time**.

The goal of this project was to build a practical budgeting tool while gaining hands-on experience with the **MERN stack (MongoDB, Express, React, Node.js)** and understanding how frontend applications communicate with backend APIs.

The application provides a simple and intuitive interface where users can:

- Record income and expenses
- Monitor their financial activity
- View their running balance
- Keep a history of all transactions

---

# 🚀 Features

✅ Add new income transactions  
✅ Add expense transactions  
✅ Automatically calculate and display running balance  
✅ View transaction history with timestamps  
✅ Color-coded transactions for income and expenses  
✅ Clean and simple user interface  
✅ Live updates by periodically fetching data from the API  

---

# 🧠 What I Practiced in This Project

This project helped strengthen my understanding of:

- Building **React frontends with state management**
- Designing and consuming **REST APIs**
- Creating a **Node.js + Express backend**
- Persisting data with **MongoDB**
- Handling asynchronous requests using **fetch and promises**
- Structuring a full-stack application

---

# 🛠️ Tech Stack

## Frontend
⚛️ React  
📜 JavaScript  
🎨 CSS  

## Backend
🟢 Node.js  
🚂 Express.js  

## Database
🍃 MongoDB  

## Other Tools
🔗 REST APIs  
⚙️ Environment variables for configuration  

---

# 🏗️ Application Architecture

The application follows a typical **MERN architecture**:

```
React Frontend
     ↓
REST API (Express / Node.js)
     ↓
MongoDB Database
```

1️⃣ The React frontend collects transaction data from the user.  
2️⃣ The data is sent to the backend API using HTTP requests.  
3️⃣ The Express server processes the request and stores the transaction in MongoDB.  
4️⃣ The frontend periodically fetches transactions to keep the UI updated.

---

# 📊 How Transactions Work

Users can create transactions by entering:

- **Amount**  
  - Positive value → Income  
  - Negative value → Expense  

- **Transaction name**

- **Description**

- **Date and time**

The application automatically calculates the **running balance** based on all recorded transactions.

---

# 📂 Project Structure

```
moneyTrackerApp
│
├── src
│   ├── api
│   │   └── models
│   │       └── Transaction.js
│   │
│   ├── App.js
│   ├── App.css
│   └── index.js
│
├── public
└── package.json
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/tyron-nyambe/moneyTrackerApp.git
```

Navigate into the project directory:

```bash
cd moneyTrackerApp
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

---

# 🔑 Environment Variables

The application uses an environment variable to connect to the backend API.

Create a `.env` file in the root directory:

```
REACT_APP_API_URL=http://localhost:4000
```

---

# 📈 Future Improvements

Some features that could be added in the future:

- 🔐 User authentication
- 📊 Spending analytics and charts
- 🏷️ Expense categories
- 💳 Budget planning tools
- 📱 Mobile-friendly UI
- ☁️ Deployment with cloud database

---

# 👨‍💻 Author

**Tyron Nyambe**

GitHub  
https://github.com/tyron-nyambe

---

⭐ If you found this project interesting, feel free to star the repository.