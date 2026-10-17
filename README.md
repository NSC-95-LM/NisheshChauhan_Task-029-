# NisheshChauhan_Task(29)

## Summary
A responsive e-commerce web application built with React 19, Tailwind CSS v4, and Vite. The application simulates an authentic sneaker store experience with a dedicated storefront, dynamic product catalog, real-time cart management using React Context API, and a streamlined payment and checkout flow.

## What it Does?
- **Interactive Product Catalog**: Showcases signature sneaker models with prices, tags, high-resolution imagery, and instant add-to-cart actions.
- **Persistent Sticky Cart Sidebar**: Keeps order summaries and running bills constantly visible alongside products while scrolling, featuring live increment, decrement, and item removal controls.
- **Context-Powered State Management**: Persists cart items and user theme preferences across page reloads via `localStorage`.
- **Streamlined Payment & Checkout**: Dedicated checkout page displaying an interactive simulated card preview, order breakdown, and simple input collection.
- **Dark & Light Mode**: Seamless theme switching with persistent storage and system-level dark mode styling.

## Project Structure
```text
Basic/
├── public/
│   ├── favicon.ico
│   └── index.html
├── src/
│   ├── assets/            # Brand logos & imagery
│   ├── components/        # Layout, Header, ProductCard, CartSidebar
│   ├── context/           # CartContext, ThemeContext
│   ├── data/              # Sneaker product catalog data
│   ├── pages/             # Shop, Payment
│   ├── App.jsx            # Application routing configuration
│   ├── main.jsx           # React root entry point
│   └── index.css          # Tailwind CSS v4 directives
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## How to Run?
1. Clone or navigate to the project directory:
   ```bash
   cd Basic
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Vite development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to the local server URL (typically `http://localhost:5173/`).

## Technologies Used
- **Frontend Framework**: React 19
- **Build Tool & Dev Server**: Vite
- **Routing**: React Router DOM (v7)
- **Styling**: Tailwind CSS (v4)
- **Icons**: Lucide React
- **State Management**: React Context API (`CartContext`, `ThemeContext`) with `localStorage` persistence

## Author
**Nishesh Chauhan**  
TuteDude MERN Full Stack Web Development - Task 29