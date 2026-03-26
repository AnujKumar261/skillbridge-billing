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

### Screenshot


<img width="1919" height="1018" alt="Screenshot 2026-03-26 140317" src="https://github.com/user-attachments/assets/37754d3d-fe3c-42e9-9100-aeda0977289c" />

<img width="1915" height="1013" alt="Screenshot 2026-03-26 135446" src="https://github.com/user-attachments/assets/46b4da4d-fd42-4206-bd68-15cd284bb0ff" />

<img width="1917" height="1014" alt="Screenshot 2026-03-26 135355" src="https://github.com/user-attachments/assets/206c3f0a-2f55-47a6-a354-ea58caec480a" />

<img width="1919" height="1016" alt="Screenshot 2026-03-26 135516" src="https://github.com/user-attachments/assets/e816a5a9-f76e-4ad7-b2c1-002c50878913" />

<img width="1918" height="1017" alt="Screenshot 2026-03-26 135503" src="https://github.com/user-attachments/assets/066d8ca6-fa8d-468c-b22d-62fe6a69408e" />

<img width="1919" height="1019" alt="Screenshot 2026-03-26 135329" src="https://github.com/user-attachments/assets/9ace5ce4-90ef-4835-a31a-7d18ac5498e2" />

<img width="1919" height="1015" alt="Screenshot 2026-03-26 135531" src="https://github.com/user-attachments/assets/d254f00f-2a56-4558-9265-2fc6ed63711a" />

<img width="1907" height="1006" alt="Screenshot 2026-03-26 135632" src="https://github.com/user-attachments/assets/8ee80c64-8e45-4126-809a-fcff78043985" />

<img width="1919" height="1018" alt="Screenshot 2026-03-26 135659" src="https://github.com/user-attachments/assets/ee079f7f-56c9-4241-8e2b-fba5826634c0" />




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
