# 🛒 Ecommerce App (Next.js)

A modern **E-commerce web application** built using **Next.js 14, React, and Tailwind CSS**.
The project demonstrates a scalable frontend architecture with product browsing, cart management, order tracking, and seller management pages.

This project is designed to simulate a real-world **online shopping platform** with modular components, state management using React Context API, and responsive UI.

---

#deployed link : https://ecommerce-app-puce-pi.vercel.app/

# 🚀 Features

### Customer Features

* Browse all products
* View individual product pages
* Add products to cart
* Manage cart items
* Place orders
* Order confirmation page
* Track previous orders
* Add and manage delivery addresses

### Seller Features

* Seller dashboard
* Seller product management pages
* Product listing for sellers

### UI / UX Features

* Responsive design
* Reusable UI components
* Toast notifications
* Product cards and banners
* Loading states

---

# 🧱 Tech Stack

### Frontend

* **Next.js 14**
* **React 18**
* **Tailwind CSS**

### State Management

* **React Context API**

### Notifications

* **react-hot-toast**

### Styling

* **TailwindCSS**
* **PostCSS**

---

# 📂 Project Structure

```
ecommerce-app
│
├── app
│   ├── add-address
│   ├── all-products
│   ├── cart
│   ├── my-orders
│   ├── order-placed
│   ├── product
│   ├── seller
│   ├── layout.js
│   └── page.jsx
│
├── components
│   ├── Banner.jsx
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   ├── ProductCard.jsx
│   ├── HomeProducts.jsx
│   ├── HeaderSlider.jsx
│   ├── FeaturedProduct.jsx
│   └── OrderSummary.jsx
│
├── context
│   └── AppContext.jsx
│
├── lib
│   └── authSeller.js
│
├── public
├── assets
├── package.json
└── tailwind.config.js
```

---

# ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/PiyushSutar-570/ecommerce_app.git
```

### 2. Go to the project directory

```bash
cd ecommerce_app
```

### 3. Install dependencies

```bash
npm install
```

### 4. Run the development server

```bash
npm run dev
```

Now open:

```
http://localhost:3000
```

---

# 🏗 Architecture Overview

The project follows a **component-based architecture** using Next.js App Router.

* **app/** → Contains all routes and pages
* **components/** → Reusable UI components
* **context/** → Global state management
* **lib/** → Utility functions and authentication logic
* **public/** → Static assets

State such as **cart items and product data** are managed using **React Context API**, allowing components across the application to access shared data.

---

# 📦 Key Components

### Navbar

Navigation across product pages, cart, and orders.

### ProductCard

Displays product image, name, and price.

### HomeProducts

Lists featured products on the homepage.

### OrderSummary

Displays checkout order details.

---

# 🌍 Deployment

The easiest way to deploy this project is using **Vercel**.

Steps:

1. Push the project to GitHub
2. Go to Vercel
3. Import the repository
4. Deploy

Your project will be live at:

```
https://your-project-name.vercel.app
```

---

# 🔮 Future Improvements

* Payment gateway integration (Stripe / Razorpay)
* Authentication system
* Backend API integration
* Product search and filtering
* Admin dashboard
* Database integration (MongoDB / PostgreSQL)
* Order tracking system

---

# 👨‍💻 Author

**Piyush Sutar**

CSE (AI & ML)
CV Raman Global University

GitHub:
https://github.com/PiyushSutar-570

---

# ⭐ Support

If you like this project, consider giving it a **star on GitHub**.
