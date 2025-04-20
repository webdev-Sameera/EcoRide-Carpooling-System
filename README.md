# 🚗 EcoRide Carpooling System

EcoRide is a full-stack carpooling platform designed to reduce traffic congestion and promote sustainable commuting by connecting drivers with passengers headed in the same direction.

---

## 🌐 Live Demo

Coming Soon...

---

## 📸 Screenshots

> You can view UI previews in the `/website-screenshots` folder.

---

## 🛠️ Features

- 🔍 Search for rides between cities
- 🚘 Drivers can offer rides and manage bookings
- 📅 Passengers can book rides and leave reviews
- 💳 Razorpay payment integration for secure transactions
- 📊 Displays popular routes and cities
- 💬 Feedback and review system

---

## 🧩 Tech Stack

### Frontend
- HTML, CSS (Bootstrap)
- JavaScript

### Backend
- Node.js (Express)
- MySQL (Database)
- Razorpay (Payments)

---

## 📂 Folder Structure

```bash
EcoRide/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   └── server.js
│
├── frontend/
│   ├── assets/
│   ├── search-rides.html
│   ├── popular-routes.html
│   ├── offer-ride.html
│   └── review.html
│
├── screenshots/
├── .gitignore
├── package.json
└── README.md

⚙️ Installation & Usage
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/webdev-Sameera/EcoRide-Carpooling-System.git
cd EcoRide-Carpooling-System
2. Setup backend
bash
Copy
Edit
cd backend
npm install
node server.js
3. Open the frontend HTML files directly in your browser
Or you can serve them with any local server if needed.

💳 Payment Gateway (Razorpay)
Integrated Razorpay for seamless transactions.

Set your Razorpay API keys in .env:

env
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret

Future Enhancements
Add authentication (JWT/Session)

Ride recommendation system

Responsive mobile-first design

Live maps & location tracking

📄 License
MIT

