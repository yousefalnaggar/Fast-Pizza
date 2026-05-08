# 🍕 Fast Pizza Co

A modern, full-featured pizza ordering web application that allows users to browse menus, manage shopping carts, place orders, and track deliveries in real-time.

## 🛠️ Tech Stack

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-593D88?style=for-the-badge&logo=redux&logoColor=white)](https://redux-toolkit.js.org/)
[![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](https://reactrouter.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)


## 📄 License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://choosealicense.com/licenses/mit/)

## 📚 Table of Contents

- [🌟 Overview](#-overview)
- [✨ Features](#-features)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [📄 License](#-license)

## 🌟 Overview

Fast Pizza Co is a comprehensive pizza ordering application built with modern React technologies. The application provides a seamless user experience for browsing pizza menus, managing shopping carts, placing orders, and tracking order status. Built with performance and user experience in mind, it features a responsive design that works perfectly across all devices.

🌐 **[Live Preview](https://your-live-demo-url.com)** - Try the application online!

The project demonstrates advanced React patterns including:
- Feature-based architecture
- Redux Toolkit for state management
- React Router for navigation
- Custom hooks and components
- API integration with error handling
- Responsive design principles

## ✨ Features

- **🍕 Interactive Menu**: Browse available pizzas with detailed information, ingredients, and pricing
- **🛒 Smart Shopping Cart**: Add, remove, and modify pizza quantities with real-time price calculations
- **👤 User Management**: Create and manage user profiles for personalized ordering experience
- **📝 Order Placement**: Intuitive order creation process with form validation
- **📍 Order Tracking**: Track order status and delivery progress with unique order IDs
- **⚡ Priority Orders**: Option to mark orders as priority for expedited delivery
- **📱 Responsive Design**: Fully responsive UI optimized for desktop, tablet, and mobile devices
- **🔄 Real-time Updates**: Live updates for order status and menu availability
- **🎨 Modern UI/UX**: Clean, intuitive interface with smooth animations and interactions

## 🚀 Getting Started

### Prerequisites

Before running this application, ensure you have:

- **Node.js** (version 18 or higher)
- **npm** or **yarn** package manager
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fast-pizza-co.git
   cd fast-pizza-co
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

### Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build for production deployment
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality checks

### Usage Guide

1. **Create User Profile**: Enter your name on the homepage to get started
2. **Browse Menu**: Explore available pizzas with detailed descriptions and pricing
3. **Add to Cart**: Select pizzas and specify quantities for your order
4. **Review Cart**: Check your selections and modify quantities if needed
5. **Place Order**: Fill in delivery details and submit your order
6. **Track Order**: Use the provided order ID to monitor delivery status

## 📁 Project Structure

```
fast-pizza-co/
├── public/                 # Static assets
├── src/
│   ├── features/          # Feature-based modules
│   │   ├── cart/         # 🛒 Shopping cart functionality
│   │   │   ├── Cart.jsx
│   │   │   ├── CartItem.jsx
│   │   │   ├── CartOverview.jsx
│   │   │   ├── DeleteItem.jsx
│   │   │   ├── EmptyCart.jsx
│   │   │   ├── UpdateItemQuantity.jsx
│   │   │   └── cartSlice.js
│   │   ├── menu/         # 🍕 Menu display and management
│   │   │   ├── Menu.jsx
│   │   │   └── MenuItem.jsx
│   │   ├── order/        # 📝 Order creation and tracking
│   │   │   ├── CreateOrder.jsx
│   │   │   ├── Order.jsx
│   │   │   ├── OrderItem.jsx
│   │   │   └── UpdateOrder.jsx
│   │   └── user/         # 👤 User management
│   │       ├── CreateUser.jsx
│   │       ├── Username.jsx
│   │       └── userSlice.js
│   ├── services/         # 🌐 API integration
│   │   └── apiRestaurant.js
│   ├── ui/              # 🎨 Reusable UI components
│   │   ├── AppLayout.jsx
│   │   ├── Button.jsx
│   │   ├── Error.jsx
│   │   ├── Home.jsx
│   │   └── LinkButton.jsx
│   ├── App.jsx          # 🚀 Main application component
│   ├── main.jsx         # 🔗 Application entry point
│   └── store.js         # 🗄️ Redux store configuration
├── package.json         # 📦 Dependencies and scripts
├── vite.config.js      # ⚡ Vite configuration
├── tailwind.config.js  # 🎨 Tailwind CSS configuration
├── eslint.config.js    # 🔍 ESLint configuration
└── README.md           # 📖 Project documentation
```

### Architecture Highlights

- **Feature-Based Organization**: Each feature (cart, menu, order, user) is self-contained with its components and state management
- **Redux Toolkit Slices**: Modular state management with dedicated slices for each feature
- **Component Reusability**: Shared UI components for consistent design and functionality
- **Service Layer**: Centralized API integration for all restaurant-related operations
- **Modern Build Setup**: Vite for fast development and optimized production builds

## 📄 License

This project is licensed under the MIT License.

---

<div align="center">
  <p><strong>Made with ❤️ by <a href="https://github.com/yousefalnaggar">Yousef Alnaggar</a></strong></p>
</div>