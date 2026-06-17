# 🛍️ E-Commerce Store

A simple and responsive **E-Commerce Web Application** developed using **HTML, CSS, JavaScript, Node.js, Express.js, and MongoDB**.

This project displays products dynamically from the backend and allows users to browse products and add them to cart.

---

## 🚀 Features

✅ Product Listing
✅ Dynamic Product Loading
✅ Add to Cart Functionality
✅ Responsive UI Design
✅ Backend API Integration
✅ Product Images Support

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js
* CORS
* MongoDB
* Mongoose

---

## 📂 Project Structure

```plaintext
E-Commerce-Store/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   │   └── productRoutes.js
│   ├── models/
│   │   └── Product.js
│   │
│   └── controllers/
│       └── productController.js
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── images/
│   ├── laptop.jpg
│   ├── mobile.jpg
│   └── headphones.jpg
│
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone <repository-url>
```

### Open Project

```bash
cd E-Commerce-Store
```

### Install Dependencies

```bash
npm install
```

### Start Server

```bash
node server.js
```

Server runs at:

```plaintext
http://localhost:5000
```

---

## ▶️ Run Frontend

Open:

```plaintext
frontend/index.html
```

Or use:

```bash
npx live-server
```

Open browser:

```plaintext
http://127.0.0.1:8080
```

---

## 📡 API Endpoints

### Home

```http
GET /
```

Response:

```json
E-Commerce Backend Running 🚀
```

---

### Get Products

```http
GET /products
```

Returns:

```json
[
{
"id":1,
"name":"Laptop",
"price":50000
}
]
```

---

## 🛒 Cart Features

* Add Products to Cart
* Store Cart using Local Storage
* View Cart Count
* Dynamic Updates

---

## 🔮 Future Improvements

* User Authentication
* Product Search
* Product Categories
* Payment Gateway
* Order Tracking
* Admin Dashboard

---

## 👨‍💻 Author

Developed by **J. Mukunda**
