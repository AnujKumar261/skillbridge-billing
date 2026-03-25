# 💼 skillbridge-billing (Full-Stack Billing System)

## 📌 Description

skillbridge-billing is a full-stack billing and invoice management system built using React (frontend) and Spring Boot (backend). It allows users to manage products, categories, customers, and orders, along with secure authentication and payment integration.

---

## 🚀 Features

* 🔐 User Authentication (JWT-based login/signup)
* 📦 Product & Category Management
* 🧾 Order & Billing System
* 👥 User Management
* 💳 Payment Integration (Razorpay)
* 📊 Dashboard with insights
* 🧮 Cart and Invoice Generation

---

## 🛠 Tech Stack

### Frontend

* React.js
* Vite
* JavaScript (ES6+)
* CSS

### Backend

* Spring Boot
* Spring Security (JWT Authentication)
* Maven

### Database

* MySQL

### Payment Gateway

* Razorpay

---

## 📂 Project Structure

```
Billing-Software/
│
├── client/              # Frontend (React)
├── billingsoftware/     # Backend (Spring Boot)
└── README.md
```

---

## ⚙️ Setup & Installation

### 🔹 1. Clone Repository

```bash
git clone  https://github.com/AnujKumar261/skillbridge-billing
cd  https://github.com/AnujKumar261/skillbridge-billing
```

---

### 🔹 2. Backend Setup (Spring Boot)

1. Open `billingsoftware` folder in IntelliJ IDEA
2. Configure database in `application.properties`
3. Run the main class:

```
BillingsoftwareApplication.java
```

---

### 🔹 3. Frontend Setup (React)

```bash
cd client
npm install
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file in the frontend if required:

```
VITE_API_URL=http://localhost:5173
```

⚠️ Do NOT upload `.env` file to GitHub. Use `.env.example` instead.

---


## 🧪 API Testing

You can test APIs using:

* Postman
* Thunder Client (VS Code extension)

---

## 📦 Build for Production

### Frontend

```bash
npm run build
```

### Backend

```bash
mvn clean install
```

---

## 🧠 Future Improvements

* 📱 Mobile responsiveness
* 🔔 Notifications system
* 📈 Advanced analytics
* 🌐 Deployment (AWS / Docker)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is for educational purposes.

---

## 👨‍💻 Author

Anuj Kumar
GitHub: https://github.com/AnujKumar261
