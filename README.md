# Stockroom — Inventory Management

A fast, modern React inventory management web application adapted from the Stockroom system.

## Features

- **Product Catalog & Inventory Tracking**: View and manage all products with SKU/ID, name (up to 80 chars), unit price, current physical stock, cumulative units sold, and reorder threshold level.
- **Fast Search & Dynamic Filtering**: Instant search across SKUs, product names, and categories, with quick filters by stock status (All, In Stock, Low Stock, Out of Stock).
- **Sell Workflow**: Quick point-of-sale modal with quantity validation against available stock, instant subtotal calculation, remaining stock preview, and transaction logging.
- **Restock Workflow**: Replenishment workflow with quick preset increments (+10, +25, +50, +100), reorder target checks, and supplier notes.
- **Stock Status & Alerts**: Dedicated dashboard highlighting items below reorder threshold and zero-unit stockouts, with batch deficit replenishment.
- **Sales & Activity Audit Log**: Full transaction history recording timestamps, action type (sale or restock), quantities, unit prices, total value, and reference notes.
- **Summary & Business Analytics**: Live metrics for Total Valuation (assets on hand), Total Realized Revenue, Inventory Turnover Ratio, category distribution, and top 5 best-selling items.
- **Import & Export**: Export inventory to CSV or JSON; import data seamlessly with validation; reset to demo defaults anytime.

## Tech Stack

- **Framework**: React 18 with TypeScript
- **Bundler & Dev Server**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Persistence**: LocalStorage with sample data initialization

## Getting Started

```bash
# Install dependencies
npm install

# Start development server on port 3000
npm run dev

# Build for production
npm run build
```
