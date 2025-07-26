# 🛍️ Forever E-Commerce

Forever E-Commerce is a modern, full-stack online shopping platform developed using the **MERN stack (MongoDB, Express.js, React, Node.js)** along with HTML, CSS, and JavaScript. It provides a seamless shopping experience with product browsing, cart management, user authentication, and secure payment integration.

---

## 📌 Features

- 🛒 **Product Browsing** – Explore a wide range of products with images and descriptions  
- 🧺 **Shopping Cart** – Add, update, and remove items from cart in real-time  
- 🔐 **User Authentication** – Register, login, and access personal account  
- 💳 **Payment Gateway** – Secure payments through Stripe or Razorpay  
- 📱 **Responsive Design** – Optimized for all screen sizes and devices  
- 📦 **Order Management** – Track past orders (user and admin functionality)  
- 🛠️ **Admin Panel** – Add/edit/delete products, manage orders and users  

---

## 🛠️ Tech Stack

| Technology         | Purpose                          |
|--------------------|----------------------------------|
| **HTML5 / CSS3**   | Page structure and layout        |
| **JavaScript**     | Client-side interactivity        |
| **Bootstrap**      | Responsive design framework      |
| **Node.js**        | Server-side runtime              |
| **Express.js**     | API routing and server logic     |
| **MongoDB**        | Database for users, products, orders |
| **Mongoose**       | MongoDB object modeling (ODM)    |
| **JWT**            | Secure token-based authentication|
| **Stripe / Razorpay** | Payment processing gateway    |

---

## 🧠 Future Enhancements
- 🗂️ Product Categories & Filtering
- 🔍 Search Functionality
- ✉️ Email Notifications (on order)
- 📈 Admin Dashboard with Charts
- 📄 Invoice PDF Downloads
- 🌐 Multi-language Support

## 📂 Folder Structure

```bash

forever_ecommerce/
├── admin/                   # Admin Panel (React + Tailwind)
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   ├── .eslintrc.cjs
│   ├── .gitignore
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   └── vite.config.js

├── backend/                 # Express.js Backend
│   ├── config/              # DB connection, payment config
│   ├── controllers/         # Route logic (auth, product, order)
│   ├── middleware/          # Auth, error handlers
│   ├── models/              # Mongoose models (User, Product, Order)
│   ├── node_modules/
│   ├── routes/              # Express routes
│   ├── server.js            # Entry point
│   ├── vercel.json          # Deployment config (optional)
│   ├── package.json
│   └── package-lock.json

├── frontend/                # Customer UI (React + Tailwind)
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   ├── .env                 # Frontend environment variables
│   ├── .eslintrc.cjs
│   ├── .gitignore
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   └── vite.config.js

├── README.md

```
---

---

## 🚀 Getting Started

```bash

1. Clone the Repository
- git clone https://github.com/vishweshjain/forever_ecommerce.git

2. Backend Setup
- cd backend
- npm install

3. Create a .env file in backend/ and add:
- PORT=5000
- MONGO_URI=your_mongodb_connection_string
- JWT_SECRET=your_jwt_secret
- STRIPE_SECRET=your_stripe_or_razorpay_key

4. Start the server:
- backend: node server.js
- frontend: npm run dev
- admin: npm run dev

```

---

## 🙋🏻‍♂️Author

- **Vishwesh Jain**
- 🔗 [LinkedIn](https://www.linkedin.com/in/vishwesh-jain/)
---
## 📄 License
- This project is licensed under the MIT License.



