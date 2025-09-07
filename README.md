 # ShopLite — Frontend‑Only E‑Commerce Store

A simple e‑commerce store built with **HTML, CSS, and vanilla JavaScript**. It runs completely in the browser using **LocalStorage** for persistence (no backend required).

## ✨ Features

- 📦 **Product Catalog** with categories, ratings, and tags
- 🔍 **Search & Filter** products by category
- ↕️ **Sorting Options** (price, rating, newest, popularity)
- 🛒 **Shopping Cart Drawer** with add, update, and remove functionality
- 💰 **Cart Summary** with GST (18%) and shipping calculation
- 🎟️ **Coupon System** (demo coupon: `SAVE10` for 10% off, up to ₹500)
- ✅ **Checkout Modal** (demo form, saves order to LocalStorage)
- 📂 **Persistent Data** — cart and orders stored in LocalStorage
- 📱 **Responsive Layout** (mobile to desktop)

## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/shoplite.git
   cd shoplite
   ```

2. Open `index.html` in your browser — no server setup required.

   > Or serve it with any static server (e.g. VS Code Live Server, Python HTTP server).

   ```bash
   python -m http.server 3000
   ```
   Then visit: [http://localhost:3000](http://localhost:3000)

## 🛠️ Customization

- **Products**: Edit the `PRODUCTS` array inside `index.html` to add your own items (name, category, price, rating, etc.).
- **Coupon Codes**: Modify the coupon logic in the script to add more discounts.
- **Styling**: Tweak the CSS in `<style>` for colors, layout, or branding.

## 📸 Screenshots

- **Home Page**: Product grid with search, filters, and sorting
- **Cart Drawer**: View and update cart with totals
- **Checkout Modal**: Demo order form

## ⚡ Tech Stack

- **HTML5**
- **CSS3** (custom styling, no frameworks)
- **JavaScript (ES6)** — LocalStorage for persistence

## 📂 Project Structure

```
shoplite/
├── index.html   # Single HTML file with inline CSS & JS
└── README.md    # Documentation
```

## 📜 License

This project is free to use and modify. Attribution is appreciated but not required.

---

⚡ Demo app — built for learning and practice. Not production‑ready. Want to expand this with a backend (Node.js, Django, etc.) and real payment gateway? Contributions are welcome!

