
# 🛍️ Smartwatch E-Commerce Platform (MERN Stack)

A full-featured and responsive e-commerce platform for smartwatches, built using the MERN stack: **MongoDB**, **Express.js**, **React.js**, and **Node.js**.

This application provides a seamless shopping experience for users and powerful management features for admins.

---

## 🚀 Features

### 👤 User Features
- View smartwatches with images, prices, and descriptions
- Add/remove items from cart
- Place orders with checkout functionality
- Responsive design for mobile & desktop

### 🛠️ Admin Features
- Add, update, and delete products
- Manage users and orders
- Image upload via Multer

---

## 🧰 Tech Stack

- **Frontend:** React, React Bootstrap, Axios
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Authentication:** JWT (JSON Web Token)
- **File Uploads:** Multer
- **Styling:** CSS, Bootstrap

---

## 📁 Project Structure

```
Smartwatch/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── upload/
│   ├── .env
│   └── index.js
└── frontend/
    ├── components/
    ├── pages/
    └── App.js
```

---

## ⚙️ Getting Started

### 📥 Clone the Repository
```bash
git clone https://github.com/Khushijain83037/Smartwatch.git
cd Smartwatch
```

### 🔧 Backend Setup
```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:
```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

Start the backend server:
```bash
npm start
```

### 💻 Frontend Setup
```bash
cd frontend
npm install
npm start
```

---

## 🌐 Application URLs

- Frontend: [http://localhost:3000](http://localhost:3000)
- Backend/API: [http://localhost:5000](http://localhost:5000)

---


## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request with improvements.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
