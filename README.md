# 🚗 EcoRide Carpooling System

EcoRide is a full‑stack carpooling platform designed to reduce traffic congestion and promote sustainable commuting by connecting drivers with passengers headed in the same direction.

---


## 📸 Screenshots

You can view UI previews in the `website-screenshots/` folder.

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

**Frontend**  
HTML, CSS (Bootstrap), JavaScript  

**Backend**  
Node.js (Express), MySQL, Razorpay  

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
│   ├── search‑rides.html
│   ├── popular‑routes.html
│   ├── offer‑ride.html
│   └── review.html
│
├── screenshots/
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Installation & Usage

1. **Clone the repository**  
   ```bash
   git clone https://github.com/webdev-Sameera/EcoRide-Carpooling-System.git
   cd EcoRide-Carpooling-System
   ```

2. **Setup backend**  
   ```bash
   cd backend
   npm install
   node server.js
   ```

3. **Open the frontend**  
   Open any of the HTML files in `frontend/` directly in your browser, or serve via Live Server.

---

## 💳 Payment Gateway (Razorpay)

Set your Razorpay API keys in a `.env` file at the project root:

```env
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret
```

---

## 🧠 Future Enhancements

- Add authentication (JWT/Session)  
- Ride recommendation system  
- Responsive mobile‑first design  
- Live maps & location tracking  

---


## 📄 License

This project is open‑source and available under the **MIT License**.

---
