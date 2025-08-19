# TradeX 🚀

**TradeX** is a full-stack stock trading platform clone built using **HTML, CSS, JavaScript, Node.js, Express, and MongoDB**.  
The goal of this project is to replicate the experience of a real trading platform with a modern responsive UI and a backend that handles user accounts, authentication, and basic trading logic.

---

## 📌 Features
- ✅ Fully responsive UI (desktop & mobile)  
- ✅ User authentication (Signup/Login with hashed passwords)  
- ✅ Dashboard for users after login  
- ✅ Ability to view stock prices (dummy data / API integration)  
- ✅ Secure session handling with JWT  
- ✅ RESTful API for users & trading operations  
- ✅ MongoDB database for persistent storage  

---

## 🛠️ Tech Stack
**Frontend:**  
- HTML5  
- CSS3 (Flexbox, Grid, Responsive Design)  
- JavaScript ( Reactused)  

**Backend:**  
- Node.js  
- Express.js  

**Database:**  
- MongoDB (Mongoose ODM)  

**Other Tools:**  
- bcrypt.js → Password hashing  
- JWT → Authentication tokens  
- dotenv → Environment variable management  

---

## 📂 Project Structure
tradex/
├── backend/
│ ├── server.js # Entry point for Express server
│ ├── routes/ # API routes (auth, users, trades, etc.)
│ ├── models/ # Mongoose models (User, Trade, etc.)
│ ├── controllers/ # Business logic
│ └── config/ # DB connection & environment setup
│
├── frontend/
│ ├── index.html # Landing page
│ ├── style.css # Stylesheet
│ ├── script.js # Client-side logic
│ └── dashboard.html # User dashboard page
│
└── package.json


---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Sowmyalt/tradex.git
cd tradex

2️⃣ Backend setup
cd backend
npm install


Run the server:

npm start

3️⃣ Frontend setup

Simply open frontend/index.html in your browser
(or serve it via Live Server in VS Code).


🌟 Future Improvements

Integrate real-time stock market data via APIs

Add trading features (buy/sell orders, portfolios)

Implement charts with Chart.js or D3.js

Deploy on Vercel (Frontend) + Render/Heroku (Backend) + MongoDB Atlas

🙌 Acknowledgements

This project was built as a full-stack practice project to strengthen both frontend and backend development skills.
