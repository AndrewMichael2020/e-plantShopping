# Paradise Nursery E-Plant Shopping

A modern, responsive e-commerce web application for browsing and shopping a curated selection of plants. Built with React, Redux Toolkit, and Vite.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Available Scripts](#available-scripts)
- [Technologies Used](#technologies-used)
- [License](#license)

## Features
- **Landing Page**: Beautiful landing page introducing Paradise Nursery.
- **About Us**: Learn about the mission and values of Paradise Nursery.
- **Product Catalog**: Browse plants by categories:
  - Air Purifying Plants
  - Aromatic Fragrant Plants
  - Insect Repellent Plants
  - Medicinal Plants
  - Low Maintenance Plants
- **Add to Cart**: Add plants to your cart. Button disables when item is in cart.
- **Cart Management**: View, increment, decrement, or remove items from your cart. See total cost.
- **Responsive Design**: Works on desktop and mobile devices.
- **State Management**: Uses Redux Toolkit for cart state.

## Demo
To run locally, see [Getting Started](#getting-started).

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AndrewMichael2020/e-plantShopping.git
   cd e-plantShopping
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production
```bash
npm run build
```
The production-ready files will be in the `dist/` directory.

### Deploy to GitHub Pages
```bash
npm run deploy
```

## Project Structure
```
├── public/                # Static assets
├── src/
│   ├── App.jsx            # Main app component
│   ├── App.css            # Main app styles
│   ├── AboutUs.jsx        # About Us section
│   ├── AboutUs.css        # About Us styles
│   ├── ProductList.jsx    # Product listing and cart logic
│   ├── ProductList.css    # Product list styles
│   ├── CartItem.jsx       # Cart item and cart view
│   ├── CartItem.css       # Cart styles
│   ├── CartSlice.jsx      # Redux slice for cart
│   ├── store.js           # Redux store setup
│   ├── main.jsx           # React entry point
│   └── index.css          # Global styles
├── index.html             # HTML entry point
├── package.json           # Project metadata and scripts
├── vite.config.js         # Vite configuration
└── README.md              # This file
```

## Usage
- **Browse Plants**: Click "Get Started" to view plant categories and products.
- **Add to Cart**: Click "Add to Cart" on any plant. The button will disable once added.
- **View Cart**: Click the cart icon in the navbar to view your cart, adjust quantities, or remove items.
- **Continue Shopping**: Use the "Continue Shopping" button in the cart to return to the product list.
- **Checkout**: The checkout button is a placeholder for future functionality.

## Available Scripts
- `npm run dev` – Start the development server
- `npm run build` – Build for production
- `npm run preview` – Preview the production build
- `npm run lint` – Lint the codebase
- `npm run deploy` – Deploy to GitHub Pages

## Technologies Used
- [React](https://react.dev/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Vite](https://vitejs.dev/)
- [ESLint](https://eslint.org/)
- [GitHub Pages](https://pages.github.com/)

## License
This project is licensed under the [Apache 2.0 License](LICENSE).