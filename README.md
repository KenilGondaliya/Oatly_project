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
<img width="3910" height="973" alt="screencapture-localhost-5173-home-2026-06-20-13_46_09" src="https://github.com/user-attachments/assets/4a1b3711-c073-4d13-851c-4722af2b1d89" />
<img width="5030" height="1010" alt="screencapture-localhost-5173-home-2026-06-20-13_46_09 (1)" src="https://github.com/user-attachments/assets/fc712bbf-ef01-423a-9607-235fc81ed388" />

### User Registration
<img width="1918" height="911" alt="Screenshot 2026-06-20 135210" src="https://github.com/user-attachments/assets/71ef5119-33c1-4c52-af71-848d153df612" />
<img width="1915" height="949" alt="Screenshot 2026-06-20 135349" src="https://github.com/user-attachments/assets/a105be86-e4db-4586-8847-89a1a521bab4" />

### Login Page
<img width="1917" height="951" alt="Screenshot 2026-06-20 135437" src="https://github.com/user-attachments/assets/0233c5de-ac16-437e-b355-eb6d0a906ce7" />

### Product Listing
<img width="1920" height="2347" alt="screencapture-localhost-5173-our-products-Ice-Cream-2026-06-20-13_57_54" src="https://github.com/user-attachments/assets/f26a4da8-dabb-47c7-9140-12d439819ab1" />

### Product Details
<img width="1920" height="3806" alt="screencapture-localhost-5173-our-products-oatgurt-676e4983588bb1466204e776-2026-06-20-13_59_25" src="https://github.com/user-attachments/assets/03d654e3-355a-4ef2-b538-2a65ee60bc2c" />

### Shopping Cart
<img width="1920" height="3094" alt="screencapture-localhost-5173-checkout-2026-06-20-14_01_30" src="https://github.com/user-attachments/assets/c8c0f49f-49cb-4e10-8942-337be4ce9940" />

### Razorpay Payment
<img width="1919" height="905" alt="Screenshot 2026-06-20 140034" src="https://github.com/user-attachments/assets/afe8db54-283b-4aba-a357-5054c11fc8a2" />

### User Dashboard
<img width="1920" height="945" alt="screencapture-localhost-5173-my-orders-2026-06-20-14_02_13" src="https://github.com/user-attachments/assets/fab01bd0-f37c-42d5-b8cb-a586afc158f0" />

### Admin Dashboard
<img width="1920" height="1375" alt="screencapture-localhost-5174-2026-06-20-14_23_27" src="https://github.com/user-attachments/assets/20dc8c9b-b730-42b8-a3d6-01d86b33f429" />

### Add Product
<img width="1920" height="1622" alt="screencapture-localhost-5174-2026-06-20-14_24_07" src="https://github.com/user-attachments/assets/7f7c5f09-b71b-411a-9f53-d9afcf1e80fd" />

### Delivery Dashboard
<img width="1920" height="945" alt="screencapture-localhost-5173-delivery-boy-2026-06-20-14_21_57" src="https://github.com/user-attachments/assets/ad1416e3-e6f2-4fbd-8c68-6c695e207e0f" />

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

**Kenil Gondaliya **

---

## 📄 License

This project is developed for educational and academic purposes.
