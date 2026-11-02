# Paradise Nursery Shopping Application

A responsive e-commerce web application for an online houseplant store called **Paradise Nursery**, developed as the Final Project for IBM's **Developing Front-End Apps with React** course.

## Project Overview

Paradise Nursery is designed to bring nature closer to plant enthusiasts by offering an intuitive shopping experience. Users can:
- Explore a categorized collection of indoor and outdoor houseplants.
- Read comprehensive plant descriptions, benefits, and pricing.
- Add plants to a global shopping cart managed with Redux Toolkit.
- Adjust item quantities, remove plants, view individual and total cart costs in real-time.
- Navigate seamlessly across landing, catalog, and checkout views.

## Features

- **Landing Page (`App.jsx`, `App.css`):**
  - Scenic greenhouse background with blurred overlay.
  - Company branding: "Welcome To Paradise Nursery - Where Green Meets Serenity".
  - Informative "About Us" section detailing company mission and values.
  - "Get Started" call-to-action button transitioning to the plant catalog.

- **Product Catalog (`ProductList.jsx`, `ProductList.css`):**
  - 30 distinct houseplants organized across 5 curated categories:
    - *Air Purifying Plants* (Snake Plant, Spider Plant, Peace Lily, Boston Fern, Rubber Plant, Aloe Vera)
    - *Aromatic Fragrant Plants* (Lavender, Jasmine, Rosemary, Mint, Lemon Balm, Hyacinth)
    - *Insect Repellent Plants* (Oregano, Marigold, Geraniums, Basil, Lavender, Catnip)
    - *Medicinal Plants* (Aloe Vera, Echinacea, Peppermint, Lemon Balm, Chamomile, Calendula)
    - *Low Maintenance Plants* (ZZ Plant, Pothos, Snake Plant, Cast Iron Plant, Succulents, Aglaonema)
  - Interactive "Add to Cart" buttons that dynamically disable and display "Added to Cart" once selected.
  - Navigation bar present on both Catalog and Cart views with links to Home, Plants, and Cart.
  - Real-time cart badge counter reflecting total item count.

- **Shopping Cart (`CartItem.jsx`, `CartSlice.jsx`, `CartItem.css`):**
  - Displays thumbnail, plant name, unit cost, quantity selector (+ / -), and line item total.
  - Automatically calculates total cart amount.
  - Delete button to remove specific plants from cart and re-enable their "Add to Cart" state.
  - "Continue Shopping" button returning directly to the catalog.
  - "Checkout" button triggering a "Coming Soon" notification.

- **State Management (`CartSlice.jsx`, `store.js`):**
  - Centralized Redux Toolkit store managing `addItem`, `removeItem`, and `updateQuantity` actions.

## Tech Stack

- **React 18**
- **Redux Toolkit & React-Redux**
- **Vite**
- **CSS3 & Responsive Design**

## Setup and Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Sanskar1319/e-plantShopping.git
   cd e-plantShopping
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## Author
- **Sanskar1319**
- IBM Developer Skills Network
