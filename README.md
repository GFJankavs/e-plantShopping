# coding-project-template

# e-plantShopping

## Paradise Nursery — Online Plant Shopping

**e-plantShopping** is a React-based e-commerce application for browsing and purchasing houseplants from Paradise Nursery. The app showcases a curated catalog of air-purifying, aromatic, low-maintenance, and pet-friendly plants, and lets shoppers add items to a cart, adjust quantities, and proceed to checkout.

## Overview

The e-plantShopping project demonstrates a complete single-page shopping experience built with modern frontend tooling. Shoppers land on a welcome page, explore plants grouped by category, and manage their selections through a cart that tracks item counts, totals, and live updates.

## Features

- Landing page with branding and a "Get Started" entry point
- Product listing with plants organized by category (e.g. Air Purifying, Aromatic, Insect Repellent, Medicinal, Low Maintenance)
- Add-to-cart action with disabled state once an item is added
- Shopping cart view to increment, decrement, or remove items
- Live cart total and per-item subtotals
- Header cart indicator showing the current number of items

## Tech Stack

- **React 18** — component-based UI
- **Redux Toolkit** & **react-redux** — global cart state management
- **Vite** — fast development server and build tool
- **ESLint** — code linting
- **gh-pages** — deployment to GitHub Pages

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Installation

```bash
git clone https://github.com/<your-username>/e-plantShopping.git
cd e-plantShopping
npm install
```

### Run locally

```bash
npm run dev
```

The app will be available at the URL printed by Vite (typically `http://localhost:5173`).

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## Project Structure

```
e-plantShopping/
├── public/             # Static assets
├── src/                # React components, Redux store, styles
├── index.html          # Vite entry HTML
├── package.json        # Project metadata and scripts
└── vite.config.js      # Vite configuration
```

## License

This project is licensed under the terms of the included [LICENSE](./LICENSE) file.
