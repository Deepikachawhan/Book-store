

# eCommerce Website

This is a fully functional eCommerce website built using **React.js** and styled with **Tailwind CSS**. The project demonstrates modern front-end web development techniques and provides a seamless shopping experience for users.

## Features

- **Responsive Design**: Adapts to all screen sizes, providing a mobile-first user experience.
- **Product Listing**: Displays a collection of products fetched dynamically.
- **Search and Filter**: Users can search for products and apply filters.
- **Product Details**: View detailed information about each product.
- **Shopping Cart**: Add, remove, and update items in the cart.
- **Checkout Flow**: Complete orders with a streamlined checkout process.
- **User Authentication**: Secure login and registration for customers.
- **Admin Panel**: Manage products, orders, and users (if implemented).

## Tech Stack

### Frontend
- **React.js**: A JavaScript library for building user interfaces.
- **React Router**: For routing and navigation.
- **Axios**: For API calls.
- **Tailwind CSS**: Utility-first CSS framework for fast and responsive styling.
- **Heroicons**: Beautiful, free SVG icons (used in conjunction with Tailwind CSS).

  ## Installation

### Prerequisites
- Node.js (>=14.x)
- npm 

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Deepikachawhan/ecommerce_website.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ecommerce_website
   ```

3. Install dependencies:
   ```bash
   npm install
   
   ```

4. Start the development server:
   ```bash
   npm start
  
   ```

5. Open your browser and go to `http://localhost:3000`.

## Folder Structure

```
├── public/            # Static files
├── src/               # Main source code
│   ├── components/    # Reusable UI components
│   ├── pages/         # Page components (Home, Product Details, etc.)
│   ├── context/       # React context for global state
│   ├── hooks/         # Custom React hooks
│   ├── services/      # API calls
│   ├── styles/        # Global styles and Tailwind CSS configuration
│   └── App.js         # Root component
├── .env               # Environment variables
├── package.json       # Project metadata and dependencies
├── tailwind.config.js # Tailwind CSS configuration
└── README.md          # Project documentation
```
## Scripts

- **`npm start`**: Starts the development server.
- **`npm run build`**: Builds the project for production.
- **`npm test`**: Runs tests (if implemented).

## Tailwind CSS Configuration

The Tailwind CSS configuration file (`tailwind.config.js`) is pre-configured with:

- Custom colors
- Responsive breakpoints
- Extended utility classes

You can customize it further as needed.

## Future Enhancements

- Integrate a payment gateway (e.g., Stripe, PayPal).
- Add a wishlist feature.
- Improve accessibility and SEO.
- Implement a progressive web app (PWA) version.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
