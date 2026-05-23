<div align="center">

# 🌊 WanderWave

</div>

## 📖 About WanderWave

**WanderWave** is a full-stack hotel booking web application that lets users browse, search, and book hotels with ease. Built with a React frontend and a Node.js + Express backend, it delivers a smooth and responsive experience across all devices.

> 💡 Whether you're planning a weekend getaway or a month-long adventure, WanderWave helps you find the perfect place to stay.

---

## ✨ Features

- 🔍 **Search & Filter** — Find hotels by location, price, dates, and ratings
- 🏨 **Hotel Listings** — Browse detailed hotel cards with images, amenities, and pricing
- 📅 **Booking System** — Select check-in/check-out dates and complete reservations
- 👤 **User Authentication** — Register, login, and manage your bookings
- 📱 **Responsive Design** — Fully optimized for mobile, tablet, and desktop
- ⚡ **Fast API** — RESTful backend with Express for quick data delivery

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React.js, HTML5, CSS3 |
| **Backend** | Node.js, Express.js |
| **API** | RESTful API |
| **Version Control** | Git & GitHub |

---

## 📁 Project Structure

```
WanderWave/
├── client/               # React frontend
│   ├── public/
│   └── src/
│       ├── components/   # Reusable UI components
│       ├── pages/        # Page-level components
│       ├── styles/       # CSS stylesheets
│       └── App.js
│
└── api/                  # Node.js + Express backend
    ├── routes/           # API route handlers
    ├── models/           # Data models
    ├── controllers/      # Business logic
    └── index.js          # Entry point
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or above)
- npm or yarn

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Vishal2501/WanderWave.git
cd WanderWave
```

**2. Set up the Backend**

```bash
cd api
npm install
npm start
```

**3. Set up the Frontend**

```bash
cd ../client
npm install
npm start
```

**4. Open in browser**

```
http://localhost:3000
```

> The API server runs on `http://localhost:8800` by default.

---

## 🌐 Environment Variables

Create a `.env` file inside the `api/` folder:

```env
PORT=8800
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```
---

<div align="center">

Made with ❤️ by [Vishal2501](https://github.com/Vishal2501)

⭐ **If you like this project, give it a star!** ⭐

</div>
