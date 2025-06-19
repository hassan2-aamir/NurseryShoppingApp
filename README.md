# Paradise Nursery - E-Plant Shopping Application

![Paradise Nursery Logo](https://cdn.pixabay.com/photo/2020/08/05/13/12/eco-5465432_1280.png)

## 🌱 Overview

Paradise Nursery is a React-based e-commerce application designed for plant enthusiasts. The application provides a user-friendly interface to browse and purchase various categories of plants including air purifying plants, aromatic fragrant plants, insect repellent plants, medicinal plants, and low maintenance plants.

## ✨ Features

- **Interactive Landing Page** with beautiful plant imagery
- **About Us Section** providing information about Paradise Nursery
- **Comprehensive Plant Catalog** organized by categories
- **Shopping Cart Functionality** with the ability to:
    - Add items to cart
    - Update item quantities
    - Remove items from cart
    - View cart total

## 🛠️ Technologies Used

- **React** - Frontend library
- **Redux Toolkit** - State management
- **CSS** - Styling
- **Vite** - Build tool

## 🚀 Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn

### Installation

1. Clone the repository
     ```bash
     git clone https://github.com/hassan2-aamir/nurseryaaplication.git
     cd paradise-nursery
     ```

2. Install dependencies
     ```bash
     npm install
     # or
     yarn install
     ```

3. Start the development server
     ```bash
     npm run dev
     # or
     yarn dev
     ```

4. Open your browser and visit `http://localhost:5173`

## 📂 Project Structure

```
e-plantShopping/
├── public/              # Static files
├── src/                 # Source files
│   ├── App.jsx          # Main application component
│   ├── AboutUs.jsx      # About us component
│   ├── CartItem.jsx     # Cart item component
│   ├── CartSlice.jsx    # Redux slice for cart functionality
│   ├── ProductList.jsx  # Product listing component
│   ├── main.jsx         # Entry point
│   ├── store.js         # Redux store configuration
│   └── ...              # CSS files and other components
├── index.html           # HTML entry point
├── package.json         # Project dependencies
└── vite.config.js       # Vite configuration
```

## 🧩 Components

- **App**: Main component that manages the landing page and product list display
- **AboutUs**: Displays information about Paradise Nursery
- **ProductList**: Displays categorized plant products
- **CartItem**: Handles cart functionality and display

## 📱 Responsive Design

The application is fully responsive, ensuring a seamless experience on:
- Desktop devices
- Tablets
- Mobile phones

## 🔄 State Management

Redux Toolkit is used for state management with the following:
- **CartSlice**: Manages cart items, quantities, and actions

## 📄 License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

## 🌿 "Where Green Meets Serenity"