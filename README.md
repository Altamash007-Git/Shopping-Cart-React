# React Shopping Cart Project

A small React shopping cart demo built with Vite.

## What this is

This project is a starter shopping cart application implemented with React and Vite. It includes components for a product list, cart, header, and a shopping cart context for state management.

## Files of interest

- `index.html` - Vite entry HTML
- `src/main.jsx` - React entry point
- `src/App.jsx` - Main app component
- `src/dummy-products.js` - Sample product data
- `src/components/Shop.jsx` - Product listing
- `src/components/Product.jsx` - Individual product item
- `src/components/Cart.jsx` - Cart display
- `src/components/CartModal.jsx` - Cart modal
- `src/components/Header.jsx` - Header with cart button
- `src/store/shopping-cart-context.jsx` - Shopping cart context and provider

## Setup (Windows PowerShell)

Open PowerShell in the project root (`d:/Code/React Shopping Cart Project`) and run:

```powershell
# install dependencies
npm install

# start dev server
npm run dev
```

If you don't have Node.js and npm installed, download them from https://nodejs.org/.

## Build for production

```powershell
npm run build
npm run preview
```

## Notes

- The project uses Vite. If you need to change port or other settings, edit `vite.config.js`.
- Feel free to add tests, TypeScript, or CI configuration as needed.

## License

This project is provided as-is for learning and demonstration purposes.