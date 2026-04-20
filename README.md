<div align="center">

<br/>

```
██╗   ██╗███████╗██╗    ██╗   ██╗███████╗████████╗██████╗ ██╗████████╗███████╗███████╗
██║   ██║██╔════╝██║    ██║   ██║██╔════╝╚══██╔══╝██╔══██╗██║╚══██╔══╝██╔════╝██╔════╝
██║   ██║█████╗  ██║    ██║   ██║█████╗     ██║   ██████╔╝██║   ██║   █████╗  ███████╗
╚██╗ ██╔╝██╔══╝  ██║    ╚██╗ ██╔╝██╔══╝     ██║   ██╔══██╗██║   ██║   ██╔══╝  ╚════██║
 ╚████╔╝ ███████╗███████╗╚████╔╝ ███████╗   ██║   ██████╔╝██║   ██║   ███████╗███████║
  ╚═══╝  ╚══════╝╚══════╝ ╚═══╝  ╚══════╝   ╚═╝   ╚═════╝ ╚═╝   ╚═╝   ╚══════╝╚══════╝
```

### 🍽️ *Food that finds you.*

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-06D6A0?style=for-the-badge)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-F5A623?style=for-the-badge)](LICENSE)

<br/>

> **VelvetBites** is a pixel-perfect, dark-themed, single-file food ordering PWA concept —  
> built entirely with vanilla HTML, CSS & JavaScript. No frameworks. No build tools. Just craft.

<br/>

![VelvetBites Preview](https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?w=900&h=400&fit=crop&q=85)

<br/>

</div>

---

## 📌 Table of Contents

- [✨ Overview](#-overview)
- [🎯 Features](#-features)
- [🖥️ Pages & Screens](#️-pages--screens)
- [🎨 Design System](#-design-system)
- [🍕 Restaurant & Menu Data](#-restaurant--menu-data)
- [🛒 Cart & Ordering Flow](#-cart--ordering-flow)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [🧩 Component Reference](#-component-reference)
- [📱 Responsive Design](#-responsive-design)
- [⚡ Performance](#-performance)
- [🔮 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ Overview

VelvetBites is a **premium food delivery UI concept** that demonstrates what modern, production-grade front-end design looks like — built entirely without frameworks. One file. Zero dependencies. Full experience.

| Metric | Value |
|---|---|
| 📦 **Bundle Size** | ~1 single HTML file |
| 🔗 **Dependencies** | Zero (CDN fonts + icons only) |
| ⚡ **Load Time** | < 1s on modern browsers |
| 📱 **Responsive** | Mobile-first, desktop-ready |
| 🍕 **Restaurants** | 12 fully populated with menus |
| 🎭 **Events** | 8 curated dining experiences |
| 🛒 **Cart Items** | Persistent across sessions (in-memory) |

---

## 🎯 Features

### 🔐 Authentication
- **Sign Up** — Full form with first/last name, email, phone, and password
- **Login** — Email/password with live validation + show/hide toggle
- **Social Auth** — Google & Apple OAuth flows (UI complete)
- **Password Strength Meter** — Animated 3-step bar with color feedback
- **Forgot Password** — Email reset trigger with toast feedback

### 🏠 Home Feed
- **Animated Aurora Background** — 6 GPU-accelerated gradient blobs
- **Category Filters** — 12 cuisine categories (All, Pizza, Burger, Sushi, Indian, Chinese, Desserts, Juices, Cocktails, Café, Healthy, Mexican)
- **Flash Sale Banner** — Promo card with coupon code (`VELVET40`)
- **Drinks Carousel** — Horizontal scroll strip for drink-only venues
- **Exclusive Deals Section** — 4 coupon cards with visual design
- **Upcoming Events Teaser** — Scrollable preview strip

### 🔍 Search & Discovery
- **Live Search** — Filters restaurants and menu items in real time
- **Trending Pills** — 10 trending keyword shortcuts
- **Global Restaurant Grid** — Full directory of all 12 venues

### 🍽️ Restaurant Detail
- **Hero Cover Image** — With gradient overlay and rating chip
- **Menu Category Tabs** — All / Bestsellers / Veg / Non-Veg
- **Menu Item Cards** — Image, description, veg/non-veg indicator, bestseller ribbon
- **Add to Cart Controls** — Inline quantity selector with `+` / `−` buttons
- **Promo Banner** — Contextual coupon nudge per restaurant

### 🛒 Cart Panel
- **Slide-in Drawer** — Smooth spring animation from the right
- **Popular Bites Strip** — 12 quick-add photo cards at the top
- **Live Item Totals** — Price updates as quantities change
- **Bill Summary** — Subtotal, free delivery, platform fee (₹5), GST (5%)
- **Coupon Row** — Tap-to-apply coupon with savings preview
- **Cross-restaurant Guard** — Confirms before replacing cart from another restaurant

### 📦 Checkout Flow
- **3-Step Progress Bar** — Cart → Delivery → Payment
- **Delivery Address Form** — Map placeholder, GPS button, address type selector
- **Payment Methods** — UPI/GPay, Credit/Debit Card, Cash on Delivery, Net Banking
- **Order Summary** — Itemized cart with thumbnails
- **Full Bill Breakdown** — With taxes and total

### 🛵 Live Order Tracking
- **Animated Map** — Grid map with live scooter position and route dashes
- **Delivery Partner Card** — Name, photo, rating, call & chat buttons
- **5-Step Timeline** — Order Placed → Accepted → Preparing → Out for Delivery → Delivered
- **ETA Countdown** — Live timer counting down from 18 minutes

### 🎭 Events & Experiences
- **8 Curated Events** — Wine & Dine, Sushi Workshop, Street Food Carnival, and more
- **Event Filters** — All / Fine Dining / Workshops / Festivals / Tastings
- **Smart Booking CTA** — Free registration or paid ticket flow

### 📅 Table Reservations
- **Restaurant Picker** — Visual card selector with cover images
- **Date & Time Pickers** — Native HTML date input + time dropdown
- **Guest Count Selector** — 1 to 6+ pill buttons
- **Special Requests** — Toggle switches for window seat, birthday, vegan menu, high chair
- **Notes Textarea** — Freeform additional requests

### 👤 Profile
- **Avatar with Edit Button** — Photo upload trigger
- **Stats Dashboard** — Orders, Bookings, Money Saved
- **Loyalty Progress Bar** — Gold → Platinum tier with points
- **Menu Grid** — Orders, Addresses, Payments, Coupons, Favourites, Support, Settings

### 📋 Order History
- **5 Past Orders** — With restaurant images, items list, totals
- **Rate + Reorder CTAs** — Per order action buttons

---

## 🖥️ Pages & Screens

| ID | Page | Description |
|---|---|---|
| `p-land` | 🌟 Landing | Hero with floating food emojis, stats, and CTAs |
| `p-login` | 🔑 Login | Email/password + social auth |
| `p-signup` | 📝 Sign Up | Full registration form with password strength |
| `p-home` | 🏠 Home | Full feed — categories, restaurants, deals, events |
| `p-rest` | 🍴 Restaurant | Menu detail with cart integration |
| `p-search` | 🔍 Search | Full directory + trending search pills |
| `p-checkout` | 💳 Checkout | 3-step: Address → Payment → Confirm |
| `p-tracking` | 🛵 Tracking | Live order map with delivery partner |
| `p-events` | 🎭 Events | Filterable event cards with booking |
| `p-reservations` | 📅 Reservations | Table booking with special requests |
| `p-profile` | 👤 Profile | User stats, loyalty tier, settings menu |
| `p-orders` | 📋 Orders | Full order history with reorder |

---

## 🎨 Design System

VelvetBites uses a cohesive **dark luxury** design language.

### Color Palette

```css
/* Backgrounds */
--bg:     #04040A   /* Deep space black    */
--s1:     #080810   /* Surface 1           */
--s2:     #0E0E1A   /* Surface 2           */
--s3:     #141420   /* Surface 3           */
--s4:     #1C1C2C   /* Surface 4           */

/* Brand Accents */
--gold:   #F5A623   /* Primary gold        */
--gold2:  #FFD166   /* Light gold          */
--coral:  #FF6B6B   /* Warm coral          */
--teal:   #06D6A0   /* Success teal        */
--violet: #7C3AED   /* Deep violet         */
--rose:   #F43F5E   /* Accent rose         */
--sky:    #0EA5E9   /* Sky blue            */

/* Typography */
--text:   #F8F4EE   /* Warm white          */
--muted:  #9090A8   /* Secondary text      */
--muted2: #58586E   /* Tertiary text       */
```

### Typography Stack

| Font | Usage | Weights |
|---|---|---|
| **Playfair Display** | Headings, restaurant names | 400, 700, 900 |
| **Syne** | UI labels, buttons, badges | 400–800 |
| **Space Grotesk** | Body text, descriptions | 300–700 |

### CSS Architecture

- **CSS Custom Properties** — All design tokens as `:root` variables
- **Glass Morphism** — `backdrop-filter: blur()` cards with semi-transparent fills
- **Utility Classes** — `.gc`, `.gcf`, `.gcd` for glass card variants
- **Badge System** — `.badge` + `.bg-gold`, `.bg-teal`, etc.
- **Button System** — `.btn-gold` (primary), `.btn-outline` (secondary), `.bico` (icon)
- **Animation Library** — `blobFloat`, `float`, `ping`, `slideUp`, `fadeScale`, `floatItem`, `gradientShift`, `shimmer`

---

## 🍕 Restaurant & Menu Data

12 restaurants fully seeded with menu items, images, ratings, and metadata:

| # | Restaurant | Cuisine | Items | Rating |
|---|---|---|---|---|
| 1 | 🌶️ Spice Garden | North Indian | 7 | 4.8 ★ |
| 2 | 🍔 Burger Republic | American · Grill | 6 | 4.6 ★ |
| 3 | 🍣 Tokyo Bites | Japanese · Sushi | 6 | 4.9 ★ |
| 4 | 🍕 Pizza Volcano | Italian · Wood-Fired | 6 | 4.7 ★ |
| 5 | 🥡 Dragon Palace | Chinese · Dim Sum | 5 | 4.5 ★ |
| 6 | 🎂 Sweet Lab | Desserts · Cakes | 8 | 4.9 ★ |
| 7 | 🥗 Green Bowl | Healthy · Vegan | 5 | 4.6 ★ |
| 8 | ☕ Brew House | Café · Coffee | 6 | 4.8 ★ |
| 9 | 🌮 Casa Mexico | Mexican · Tex-Mex | 5 | 4.5 ★ |
| 10 | 🧃 Pure Juice Bar | Cold Press · Wellness | 7 | 4.7 ★ |
| 11 | 🍹 The Mixology Lab | Cocktails · Bar | 7 | 4.8 ★ |
| 12 | 🎂 Cake Studio | Cakes · Pastries | 7 | 4.9 ★ |

Each restaurant object includes: `id`, `name`, `cuisine`, `rating`, `reviews`, `delivery time`, `price for 2`, `discount tag`, `cover image`, and a full `items[]` array with name, description, price, veg flag, popular flag, and image.

---

## 🛒 Cart & Ordering Flow

```
Browse Menu → Add Items → Cart Panel → Checkout → Address → Payment → Tracking
```

**Cart State (in-memory object):**
```javascript
cart = {
  [itemId]: {
    id, name, desc, price, veg, img,
    rName, rId,   // source restaurant
    qty           // current quantity
  }
}
```

**Key Cart Functions:**

| Function | Description |
|---|---|
| `addItem(id)` | Adds item to cart; prompts on cross-restaurant conflict |
| `chgQty(id, delta)` | Increments or decrements quantity; removes if 0 |
| `getTotal()` | Returns sum of `price × qty` for all items |
| `getCount()` | Returns total item count for badge |
| `updateCartPanel()` | Re-renders cart drawer HTML |
| `updateCC()` | Updates cart count badge on nav icons |
| `openCart()` / `closeCart()` | Toggles drawer with overlay |

---

## 🚀 Getting Started

No installation. No build step. No package manager.

### Option 1 — Open Directly
```bash
# Just open the file in any browser
open index.html
```

### Option 2 — Local Server (recommended)
```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .

# VS Code — use the Live Server extension
```

Then visit `http://localhost:8000`

### Option 3 — GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app will be live at `https://yourusername.github.io/velvetbites`

---

## 📁 Project Structure

```
velvetbites/
│
├── index.html          ← Entire application (HTML + CSS + JS)
│
├── README.md           ← This file
└── LICENSE             ← MIT License
```

> **Why single-file?** This project demonstrates that a complete, production-quality UI can be built without a build pipeline. The entire app — styles, logic, data, and markup — lives in one portable, shareable file.

---

## 🧩 Component Reference

### Navigation Functions

```javascript
nav('p-home')        // Navigate to a page (adds to history stack)
goBack()             // Pop history stack and return
initPage(id)         // Called after every nav — renders page-specific content
```

### Toast Notification

```javascript
toast('🎉 Order placed!')   // Shows a bottom toast for 2.8 seconds
```

### Page Renderers

```javascript
renderRest(list)             // Renders restaurant grid cards
renderSGrid(list)            // Renders search page grid
renderEvents(list)           // Renders events grid with filters
renderEvTeaser()             // Renders scrollable events strip on home
renderDetail()               // Renders full restaurant detail + menu
menuCard(item)               // Returns HTML string for a single menu item
restCard(r)                  // Returns HTML string for a restaurant card
renderOrders()               // Renders order history list
buildProfMenu()              // Builds profile settings menu
```

### Filter Functions

```javascript
catF('pizza', btn)           // Filter restaurants by category
menuCat('popular', btn)      // Filter menu items by type
evF('workshop', btn)         // Filter events by type
searchR('biryani')           // Full-text search across restaurants + items
```

---

## 📱 Responsive Design

VelvetBites is built **mobile-first** with responsive breakpoints:

| Breakpoint | Layout |
|---|---|
| `< 768px` | Single column · Bottom nav · Mobile search |
| `≥ 768px` | Multi-column grids (2, 3, 4 col) · Top nav search |

**Responsive utilities:**
- `.hide-d` — Hidden on desktop, visible on mobile
- `.hide-m` — Hidden on mobile, visible on desktop
- `.g2`, `.g3`, `.g4` — Responsive grid helpers (desktop only)
- `clamp()` — Used on hero headline for fluid font scaling

**Bottom Navigation** (`p-home`, `p-search`, `p-events`, `p-reservations`, `p-profile`) — 72px fixed, glass-morphism background, active state with golden glow.

---

## ⚡ Performance

| Technique | Implementation |
|---|---|
| **CSS animations** | `will-change: transform` on aurora blobs |
| **Lazy loading** | `loading="lazy"` on all `<img>` tags |
| **No reflows** | Transforms only — no layout-triggering properties |
| **CDN assets** | Google Fonts, Font Awesome, Unsplash images |
| **No JS frameworks** | Zero parse/compile overhead |
| **Debounced search** | Filters fire on `oninput` (native, fast) |
| **Backdrop blur** | GPU-composited `backdrop-filter` for glass cards |

---

## 🔮 Roadmap

| Status | Feature |
|---|---|
| ✅ | Full UI with 12 pages |
| ✅ | Cart system with cross-restaurant guard |
| ✅ | 3-step checkout flow |
| ✅ | Live order tracking screen |
| ✅ | Event booking system |
| ✅ | Table reservation form |
| 🔲 | Backend API integration (Node.js / Supabase) |
| 🔲 | Real authentication (JWT / OAuth) |
| 🔲 | Persistent cart (localStorage / IndexedDB) |
| 🔲 | Real-time order tracking (WebSockets) |
| 🔲 | Push notifications (Service Worker) |
| 🔲 | Payment gateway (Razorpay / Stripe) |
| 🔲 | Admin dashboard |
| 🔲 | PWA manifest + offline support |
| 🔲 | Accessibility audit (WCAG 2.1 AA) |

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

```bash
# 1. Fork the repository
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/velvetbites.git
cd velvetbites

# 3. Create a feature branch
git checkout -b feature/your-feature-name

# 4. Make your changes to index.html
# 5. Commit with a descriptive message
git commit -m "feat: add dark mode toggle"

# 6. Push and open a Pull Request
git push origin feature/your-feature-name
```

**Contribution Guidelines:**
- Keep the zero-dependency philosophy intact for UI-only changes
- Follow the existing CSS variable system — don't hardcode colors
- All new restaurant/menu data should use Unsplash images with `?w=&h=&fit=crop` params
- Toast every user action with a descriptive emoji message
- Test on both mobile (375px) and desktop (1440px) viewports before submitting

---

## 📄 License

```
MIT License

Copyright (c) 2025 VelvetBites

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

<div align="center">

<br/>

**Built with 🔥 and zero dependencies**

*VelvetBites — Food that finds you.*

<br/>

[![Star this repo](https://img.shields.io/github/stars/yourusername/velvetbites?style=social)](https://github.com/yourusername/velvetbites)
[![Fork this repo](https://img.shields.io/github/forks/yourusername/velvetbites?style=social)](https://github.com/yourusername/velvetbites/fork)

<br/>

</div>
