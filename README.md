# MERN Admin Dashboard

Welcome to my signature MERN Admin Dashboard – a project crafted with passion, precision, and a vision for modern business intelligence. This application is a reflection of my commitment to clean code, scalable design, and empowering users with actionable insights.

I built this dashboard from the ground up, leveraging the power of MongoDB, Express, React, and Node.js to deliver a seamless, robust, and visually compelling admin experience. Every feature, every line of code, and every UI detail is a testament to my dedication as a developer.

---

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Setup & Installation](#setup--installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)
- [About the Author](#about-the-author)

---

## Features
- Modern, responsive admin UI designed by me
- User, product, transaction, and sales management
- Data visualization: bar, line, pie, and geo charts
- Role-based access (admin, superadmin, user)
- RESTful API with Express & MongoDB
- Redux Toolkit Query for state management & data fetching
- Authentication-ready (extendable)
- Modular, scalable codebase

---

## Tech Stack
**Frontend:**
- React 18
- Material UI 5
- Redux Toolkit & RTK Query
- React Router 6
- Nivo Charts

**Backend:**
- Node.js 18+
- Express 4
- MongoDB (Mongoose ODM)
- Helmet, Morgan, CORS, Dotenv

---

## Project Structure
```
Mern-Dashboard/
├── client/          # React frontend
│   ├── src/
│   ├── public/
│   └── ...
├── server/          # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── data/
│   └── index.js
└── README.md
```

---

## Setup & Installation
### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- MongoDB instance (local or cloud)

### Clone the repository
```bash
git clone <this-repo-url>
cd Mern-Dashboard
```

### Install dependencies
#### Client
```bash
cd client
npm install
```
#### Server
```bash
cd ../server
npm install
```

---

## Environment Variables
Create a `.env` file in the `server/` directory:
```
MONGO_URL=your-mongodb-connection-string
PORT=9000 # or any port
```

---

## Usage
### Start the backend server
```bash
cd server
npm run dev
```

### Start the frontend
```bash
cd ../client
npm start
```

- The React app runs on [http://localhost:3000](http://localhost:3000)
- The Express API runs on [http://localhost:9000](http://localhost:9000)

---

## API Endpoints
- `/client/products` - Get all products with stats
- `/client/customers` - Get all customers
- `/client/transactions` - Get paginated transactions
- `/client/geography` - Get user distribution by country
- `/general`, `/management`, `/sales` - See corresponding routes for more

---

## Contributing
1. Fork the repo
2. Create your feature branch (`git checkout -b feature/awesome-feature`)
3. Commit your changes (`git commit -m 'Add awesome feature'`)
4. Push to the branch (`git push origin feature/awesome-feature`)
5. Open a Pull Request
