# 🛒 Birwal-KART

**Birwal-KART** is a full-stack **MERN-based e-commerce platform** enabling seamless product listing, user interaction, and real-time complaint handling. Built for fast browsing, efficient buying/selling, and modular extensibility.

---

## 🚀 Features

- 🛍 Add products without login
- 🔐 JWT-based user authentication
- 💬 Real-time complaint system via Socket.io
- 🔄 Buy & Sell functionality with full CRUD support
- 📦 MongoDB-based data structure with manual seeding option

---

## 🛠 Tech Stack

- **Frontend**: React.js, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Real-time**: Socket.io

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/iamsumitkumar64/Birwal-KART.git
cd Birwal-KART
```

### 2. Install Dependencies

```bash
npm i
```

### 3. Start the Application

```bash
npm start
```

---

## 🗃 MongoDB Manual Data Import (Optional)

To manually populate the database with sample users and products:

1. Ensure your MongoDB server is running
2. Use MongoDB Compass or CLI to import the JSON files provided in the repo

### ✅ Files for Import

- **Users** → `ECOMMERCE.user.json` → `user` collection  
- **Products** → `ECOMMERCE.product.json` → `product` collection

You can find both files in the root of the project repository.

---

## 📌 Notes

- This project is for learning/demo purposes
- Real-time features (like complaints) require a working Socket.io connection
- You can add products even without logging in, but buying/selling requires authentication

---

## 👨‍💻 Author

**Sumit Birwal**  
GitHub: [@iamsumitkumar64](https://github.com/iamsumitkumar64)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE)
