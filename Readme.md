# 🛒 E-Mart – React E-Commerce Application

## 📌 Project Overview

E-Mart is a responsive e-commerce web application built using **React.js**.
It allows users to browse products across multiple categories, filter items, view detailed product information, and manage a shopping cart.

---

## 🚀 Features

* 🏠 Landing page with product previews
* 📱 Category-wise product listing (Mobiles, Computers, Watches, etc.)
* 🔍 Filter products by company (e.g., Apple, Samsung)
* 📄 Dynamic product detail pages
* 🛒 Add to Cart functionality using global state
* 🔢 Real-time cart item count in Navbar
* 🔗 Client-side routing using React Router

---

## 🧠 Tech Stack

* **Frontend:** React.js
* **Routing:** React Router DOM
* **State Management:** Context API
* **Styling:** CSS
* **Build Tool:** Vite

---

## 📂 Project Structure

```
src/
│
├── components/        # Reusable UI components (Navbar, Products, etc.)
├── pages/             # Category pages (MobilePage, CompPage, etc.)
├── singles/           # Single product detail pages
├── context/           # CartContext for global state
├── data/              # Static product data
├── App.jsx            # Routing configuration
├── main.jsx           # Entry point
```

---

## 🔄 Application Flow

```
Landing Page
   ↓
Select Category
   ↓
Product Listing Page (with filters)
   ↓
Click Product
   ↓
Product Detail Page
   ↓
Add to Cart
   ↓
Cart Page
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```
git clone https://github.com/your-username/e-mart.git
```

2. Navigate to project folder:

```
cd e-mart
```

3. Install dependencies:

```
npm install
```

4. Run the project:

```
npm run dev
```

---

## 🧩 Key Concepts Used

* Component-based architecture
* React Hooks (`useState`, `useContext`, `useParams`)
* Dynamic Routing
* Conditional Rendering
* Array methods (`map`, `filter`)
* Global state management using Context API

---

## 💡 Future Improvements

* Add quantity management in cart
* Implement user authentication
* Integrate backend (Spring Boot / Node.js)
* Add payment gateway
* Improve UI with animations

---

## 👨‍💻 Author

**Sai (Bhargav Sai)**
Final Year Engineering Student

---

## ⭐ Conclusion

This project demonstrates a complete frontend e-commerce workflow including product listing, filtering, dynamic routing, and cart management using modern React practices.
