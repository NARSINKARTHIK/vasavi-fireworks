# 🎆 Vasavi Fireworks

A modern, responsive, Diwali-themed e-commerce website for Vasavi Fireworks store. Built with HTML, CSS, and JavaScript — no build tools or server required.

## ✨ Features

- 🎇 Live animated fireworks background
- ⏱️ Diwali countdown timer
- 🔍 Product search, category filter, price filter, sort
- 🛒 Shopping cart with quantity controls and live totals
- 💬 WhatsApp order integration (sends formatted order message)
- 📋 Customer details form with validation (name, phone, address, city, state, pincode)
- 📱 Fully mobile responsive
- 🌙 Dark / Light theme toggle
- ❤️ Wishlist
- 📊 Admin dashboard (orders, popular products) — stored in browser localStorage
- 109+ real products across 8 categories (Sparklers, Fancy Crackers, Flower Pots, Ground Chakkars, Laxmi Bombs, Atom Bombs, String Crackers, Rockets)

## 🚀 Live Site

Deployed on Netlify: `https://vasavifireworks.netlify.app` (rename as needed in Netlify settings)

## 📁 Project Structure

```
vasavi-fireworks/
├── index.html      # Entire website (HTML + CSS + JS in one file)
└── README.md       # This file
```

## 🛠️ How to Run Locally

Just open `index.html` in any browser. No installation needed.

## 🌐 How to Deploy

### Option A — Netlify (recommended, free)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `index.html`
3. Get instant live link

### Option B — GitHub Pages (free)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Source: **Deploy from branch** → `main` → `/ (root)`
4. Save — your site goes live at `https://yourusername.github.io/vasavi-fireworks`

## ✏️ How to Update Products

All products are defined in the `PRODUCTS` array inside the `<script>` tag in `index.html`. Each product looks like:

```js
{id: 1, name: 'Pop Ups', category: 'Fancy Crackers', qty: '50pcs', price: 10, emoji: '🎊'}
```

To add a new product, copy this format and add a new line to the array. To add a new category, just use a new `category` name — it will automatically appear in the category filter bar.

## 📞 WhatsApp Order Number

Update this line in `index.html` to change the order recipient number:

```js
const WHATSAPP_NUMBER = '919989113213';
```

## 📍 Store Details

Update store location, phone, and hours in the **Contact Us** section of `index.html`.

## 📝 License

This project is for Vasavi Fireworks store use.
