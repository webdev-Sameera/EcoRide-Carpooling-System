```markdown
# 🚗 EcoRide - Carpooling System

EcoRide is a modern web-based carpooling system that connects riders and drivers for shared travel, aiming to reduce carbon emissions and ease traffic congestion.

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
```

---

## 📸 Screenshots

> UI previews and design flows are available in the `website-screenshots/` folder.

---

## ⚙️ Setup Instructions

### 1. **Clone the Repository**

```bash
git clone https://github.com/webdev-Sameera/EcoRide-Carpooling-System.git
cd EcoRide-Carpooling-System
```

---

### 2. **Backend Setup**

```bash
cd backend
npm install
```

#### 🔐 Environment Variables

Create a `.env` file inside `backend/` and add your Razorpay credentials:

```ini
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret
```

---

### 3. **Run Backend**

```bash
node server.js
```

---

### 4. **Frontend**

Open any HTML file inside `frontend/` directly in a browser,  
or use a **Live Server** extension in VSCode.

---

## 🛠 Database Setup

- Configure your MySQL database inside backend files (e.g., `server.js`)
- Create required tables for:
  - `users`
  - `rides`
  - `bookings`
  - `reviews`

---

## 📌 To-Do & Future Enhancements

- Add user authentication (JWT)
- Make UI fully responsive for mobile
- Google Maps or live tracking integration
- Email/SMS confirmations for bookings

---

## 🤝 Contributing

Contributions, suggestions, and issues are welcome!  
Please open a pull request or raise an issue for discussion.

---

## 📄 License

MIT
```
