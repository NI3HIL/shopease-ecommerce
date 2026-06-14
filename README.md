# ShopEase - Full-Stack MERN E-Commerce Platform

## 🔗 Live Demo
Access the live application here: **[https://shopease-ecommerce-frontend.vercel.app](https://shopease-ecommerce-frontend.vercel.app)**

ShopEase is a modern, responsive full-stack e-commerce application built using the MERN stack (MongoDB, Express.js, React, Node.js). It features a complete shopping flow, user authentication, profile settings, and an administrative panel for catalog and order management.

## 🚀 Key Features

* **Complete Shopping Flow:** Browse products, search by keywords, filter by categories, and add items to a persistent shopping cart.
* **Responsive UI:** Built with React Bootstrap and styled with a custom violet theme. Responsive design works seamlessly on desktop, tablet, and mobile devices.
* **Secure Authentication:** JWT-based user authentication for secure sign-up, sign-in, and profile updates.
* **Checkout Workflow:** Step-by-step wizard for managing shipping addresses, selecting payment methods (PayPal/Stripe integrations), and placing orders.
* **Admin Dashboard:** Access controls for admins to monitor sales charts, manage products (create/edit/delete), handle orders (view/deliver status), and edit user details.

## 🛠️ Tech Stack

* **Front-End:** React.js, React Router, React Bootstrap, Axios, React Helmet Async (SEO)
* **Back-End:** Node.js, Express.js, MongoDB & Mongoose (ODM), JWT (JSON Web Tokens), bcryptjs
* **Services:** Mailgun (Transactional emails)

---

## 💻 Local Installation & Setup

Follow these steps to run the project locally on your machine.

### Prerequisites
- Node.js (v18 or higher recommended)
- MongoDB (local community edition or Atlas connection string)

### 1. Clone & Install Dependencies
```bash
git clone https://github.com/NI3HIL/shopease-ecommerce.git
cd shopease-ecommerce
npm install
```

### 2. Configure Environment Variables
Create a `.env` file in the `backend` folder and add the following:
```env
PORT=5000
MONGODB_URI=mongodb://localhost/shopease
JWT_SECRET=somethingsecret
PAYPAL_CLIENT_ID=sb
```

### 3. Seed Database with Initial Data
Run the seeding tool to populate sample products and create default users:
```bash
npm run seed
# Or visit http://localhost:5000/api/seed in your browser after starting the backend
```

### 4. Run the Application
Start both the backend server and frontend development server:
```bash
# In the root directory:
npm run build
npm start
```
* **Frontend:** Runs on `http://localhost:3000`
* **Backend API:** Runs on `http://localhost:5000`

---

## 📄 License
This project is open-source and available under the MIT License.
