# 🌿 Paradise Nursery - E-Plant Shopping

## Overview

Paradise Nursery is a React and Redux-based shopping cart application that allows users to browse and purchase a variety of indoor house plants. The application provides an intuitive shopping experience with categorized plant listings, a dynamic shopping cart, and real-time cart updates using Redux Toolkit.

---

## Features

* Beautiful landing page introducing Paradise Nursery.
* Navigation bar with links to:

  * Home
  * Product Listing
  * Shopping Cart
* Browse plants organized into multiple categories.
* View plant details including:

  * Image
  * Name
  * Description
  * Price
* Add plants to the shopping cart.
* Prevent duplicate additions by disabling the "Add to Cart" button after a product is added.
* Increase or decrease item quantity in the cart.
* Remove items from the cart.
* Display total number of items.
* Calculate and display the total cart value dynamically.
* Continue Shopping and Checkout buttons.

---

## Technologies Used

* React
* React Router
* Redux Toolkit
* React Redux
* JavaScript (ES6+)
* HTML5
* CSS3

---

## Project Structure

```text
src/
│
├── components/
│   ├── AboutUs.jsx
│   ├── ProductList.jsx
│   ├── CartItem.jsx
│   ├── Navbar.jsx
│
├── redux/
│   ├── CartSlice.jsx
│   ├── store.js
│
├── App.jsx
├── App.css
└── main.jsx
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/e-plantShopping.git
```

Navigate to the project folder:

```bash
cd e-plantShopping
```

Install dependencies:

```bash
npm install
```

Run the application:

```bash
npm start
```

or, if using Vite:

```bash
npm run dev
```

---

## Usage

1. Open the application.
2. Click **Get Started** on the landing page.
3. Browse available plants.
4. Click **Add to Cart** to add a plant.
5. Open the shopping cart.
6. Increase or decrease item quantities.
7. Remove items if needed.
8. Review the total cost.
9. Continue shopping or proceed to checkout.

---

## Learning Objectives

This project demonstrates:

* React functional components
* Component composition
* React Hooks (`useState`)
* Redux Toolkit state management
* React Router navigation
* Dynamic rendering using `map()`
* Event handling
* Conditional rendering
* Responsive UI development

---

## Screenshots

You may include screenshots of:

* Landing Page
* Product Listing Page
* Shopping Cart Page

---

## Future Improvements

* User authentication
* Product search and filtering
* Wishlist functionality
* Payment gateway integration
* Order history
* Backend API integration
* Persistent cart using Local Storage

---

## License

This project was developed for educational purposes as part of the IBM React Final Project.
