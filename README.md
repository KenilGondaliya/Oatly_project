# 🥛 Oatly - Plant-Based Dairy E-Commerce Platform

## 📖 Overview

Oatly is a full-stack e-commerce platform developed for selling plant-based dairy products online. The platform provides a seamless shopping experience with secure authentication, online payments, real-time order tracking, and dedicated dashboards for customers, administrators, and delivery personnel.

Built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js), Oatly focuses on scalability, security, and user experience while promoting sustainable and eco-friendly dairy alternatives.

---

## ✨ Features

### 👤 User Features

* User Registration & Login
* JWT Authentication
* Email Verification & OTP Validation
* Forgot Password & Reset Password
* Profile Management
* Product Browsing
* Product Search & Filtering
* Shopping Cart Management
* Secure Checkout
* Order History
* Real-Time Order Tracking

### 🛒 Product Features

* Product Categories
* Product Details Page
* Product Images & Descriptions
* Product FAQs
* Dynamic Product Management

### 💳 Payment Features

* Razorpay Payment Gateway Integration
* UPI Payments
* Debit/Credit Card Payments
* Net Banking Support
* Secure Payment Processing

### 🚚 Delivery Boy Features

* Delivery Partner Registration
* Assigned Order Management
* Update Delivery Status
* Real-Time Delivery Tracking

### 🔧 Admin Features

* Dashboard Management
* Product CRUD Operations
* User Management
* Delivery Boy Management
* Order Management
* Inventory Control

---

## 🏗️ System Architecture

Frontend (React.js + Tailwind CSS)
⬇
Backend API (Node.js + Express.js)
⬇
MongoDB Atlas Database
⬇
Razorpay Payment Gateway

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* ShadCN UI
* Zustand
* Axios
* React Router DOM

### Backend

* Node.js
* Express.js
* JWT Authentication
* Socket.io
* Cloudinary

### Database

* MongoDB Atlas

### Payment Gateway

* Razorpay
---

## 📂 Project Modules

### User Module

* Registration
* Login
* Profile Management
* Product Purchase
* Order Tracking

### Admin Module

* Product Management
* User Management
* Delivery Boy Management
* Order Monitoring

### Delivery Boy Module

* Order Assignment
* Delivery Updates
* Real-Time Status Management

### Payment Module

* Secure Transactions
* Payment Verification
* Order Confirmation

---

## 🔐 Authentication Features

* JWT Authentication
* Protected Routes
* Password Encryption
* Email Verification
* OTP Verification
* Forgot Password
* Reset Password

---

## 📡 Real-Time Tracking

Socket.io is used to provide real-time order status updates:

* Pending
* Assigned
* Out for Delivery
* Delivered

Customers can monitor order progress instantly without refreshing the page.

---

## 🗄️ Database Collections

### Users

Stores:

* User Information
* Authentication Details
* Address Information
* User Roles

### Products

Stores:

* Product Information
* Product Images
* Categories
* Pricing

### Orders

Stores:

* Ordered Products
* Payment Information
* Delivery Information
* Tracking Status

### Delivery Boys

Stores:

* Delivery Partner Details
* Vehicle Information
* Availability Status
* Delivery Statistics

---

## 📸 Project Screenshots

### Home Page

<img width="1435" height="934" alt="Screenshot 2025-03-09 202112" src="https://github.com/user-attachments/assets/f73c85aa-feb5-414f-b54e-4d667e76170e" />


### User Registration

![Registration](./screenshots/register.png)

### Login Page

![Login](./screenshots/login.png)

### Product Listing

![Products](./screenshots/products.png)

### Product Details

![Product Details](./screenshots/product-details.png)

### Shopping Cart

![Cart](./screenshots/cart.png)

### Razorpay Payment

![Payment](./screenshots/payment.png)

### User Dashboard

![User Dashboard](./screenshots/user-dashboard.png)

### Admin Dashboard

![Admin Dashboard](./screenshots/admin-dashboard.png)

### Add Product

![Add Product](./screenshots/add-product.png)

### Delivery Dashboard

![Delivery Dashboard](./screenshots/delivery-dashboard.png)

### Order Tracking

![Order Tracking](./screenshots/order-tracking.png)

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/oatly.git
cd oatly
```

### Backend Setup

```bash
cd backend

npm install

npm run dev
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret

CLIENT_URL=http://localhost:5173
```

---

## 🚀 Future Enhancements

* GPS-Based Live Delivery Tracking
* Product Reviews & Ratings
* Wishlist Functionality
* AI Product Recommendations
* Push Notifications
* Multi-Vendor Support
* Mobile Application

---

## 🎯 Objectives

* Provide seamless online shopping for Oatly products.
* Ensure secure transactions.
* Enable real-time order tracking.
* Simplify product and order management.
* Promote sustainable plant-based living.

---

## 👨‍💻 Author

**Gondaliya Kenil Ashokbhai**

Bachelor of Computer Application (BCA)

Atmanand Saraswati Science College

Academic Year: 2024-25

---

## 📄 License

This project is developed for educational and academic purposes.
