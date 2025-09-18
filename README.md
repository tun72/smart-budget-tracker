
## 📊 Smart Budget Tracker

A full-stack budget tracking application built with the **MERN** stack (MongoDB, Express, React, Node.js) using **TypeScript**. It allows users to manage their income and expenses with a modern and responsive UI.

---

### 📁 Project Structure

```
smart-budget-tracker/
│
├── frontend/   # React + TypeScript frontend
├── server/     # Express + TypeScript backend
├── README.md
└── ...
```

---

### 🧰 Tech Stack

* **Frontend**: React, TypeScript, Redux (optional), TailwindCSS or CSS Modules
* **Backend**: Node.js, Express, TypeScript
* **Database**: MongoDB (Mongoose)
* **Authentication**: JWT (if applicable)
* **API Testing**: Postman / Thunder Client

---

### 🚀 Getting Started

#### 📦 Prerequisites

Ensure you have the following installed:

* [Node.js](https://nodejs.org/) (v18+ recommended)
* [MongoDB](https://www.mongodb.com/)
* [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)

---

### ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/smart-budget-tracker.git
cd smart-budget-tracker
```

2. **Install frontend dependencies**

```bash
cd frontend
npm install  # or yarn install
```

3. **Install backend dependencies**

```bash
cd ../server
npm install  # or yarn install
```

---

### 🧪 Environment Variables

Create a `.env` file in the `/server` directory with the following:

```
MONGO_URI=mongodb://localhost:27017/finance
GEMINI_API_KEY=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
RESEND_API_KEY=
FRONTEND_ORIGIN=http://localhost:5173
```

Create a `.env` file in the `/frontend` directory (optional) for React config:

```
VITE_API_URL=http://localhost:4000/api
```

---

### ▶️ Running the App

#### Run **frontend** (React app)

```bash
cd frontend
npm run dev  # or yarn dev
```

Frontend runs on: `http://localhost:5173`

#### Run **backend** (Express server)

```bash
cd server
npm run dev  # or yarn dev
```

Backend runs on: `http://localhost:5000`

---

### 🔧 Scripts

#### Frontend

| Command         | Description              |
| --------------- | ------------------------ |
| `npm run dev`   | Start React dev server   |
| `npm run build` | Build production version |
| `npm run lint`  | Run linter               |

#### Server

| Command         | Description             |
| --------------- | ----------------------- |
| `npm run dev`   | Run server with Nodemon |
| `npm run build` | Compile TypeScript      |
| `npm start`     | Start compiled server   |

---

### ✅ Features

* Add, edit, delete income and expenses
* Monthly budget overview
* Category-wise breakdown
* Dark mode support (optional)
* JWT-based user authentication (if included)
* Responsive dashboard

---

### 📌 Todo

* [ ] Add recurring transactions
* [ ] Export to CSV
* [ ] Add unit and integration tests

---

### 🛠️ Tools Used

* VSCode
* Postman
* MongoDB Atlas
* Vite (for frontend)
* Nodemon / ts-node-dev (for backend)

---
