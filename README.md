# This is a test access made by Zeenie AI automation agent| La Douceur | Luxury Sweet Shop

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge&logo=responsive)](https://en.wikipedia.org/wiki/Responsive_web_design)
[![License](https://img.shields.io/badge/License-MIT-gold?style=for-the-badge)](LICENSE)

An elegant, fully responsive, and modern single-page website for **La Douceur**, a premium Parisian luxury sweet shop. Handcrafted using semantic **HTML5** and modern **CSS3** (incorporating Flexbox, CSS Grid, custom properties, and smooth animations) with zero heavy external dependencies.

> *"Creating moments of pure luxury and sweetness since 1924. Experience the haute couture of French confectionery."*

---

## ✨ Key Features

### 1. 🧭 Elegant & Responsive Navigation
* **Sticky Navigation**: A clean, minimalist header that starts transparent and smoothly transitions into a beautiful glassmorphic solid cream background (`backdrop-filter: blur(15px)`) upon scrolling.
* **Scroll-Active Highlighting**: Navigation links dynamically highlight based on the section currently visible on the screen.
* **Mobile Hamburger Menu**: A fully custom, animated mobile drawer menu triggered by a hamburger icon, ensuring an outstanding mobile browsing experience.

### 2. 🎭 Cinematic Hero Section
* **Immersive Visuals**: A full-height, high-quality bakery background overlayed with a warm, subtle dark gradient for high text readability.
* **Refined Typography**: Uses a high-contrast combination of *Playfair Display* (Serif) and *Montserrat* (Sans-Serif) to convey luxury.
* **Micro-interactions**: Prominent, dual call-to-action (CTA) buttons with smooth hover transformations and a delicate, animated scrolling-mouse indicator guiding users downward.

### 3. 📖 "Our Story" Split Layout
* **Heritage Storytelling**: Elegant editorial layout sharing the rich background of the shop, complete with a beautiful, authentic signature block for the master pâtissier.
* **Offset Image Framing**: A gorgeous, offset-bordered image displaying artisan pastry preparation, using layered CSS positioning.

### 4. 🌟 Value Props Banner
* Highlights core brand pillars (*Organic Ingredients*, *Artisanal Craft*, and *Luxury Packaging*) using custom-styled, elegant **FontAwesome** icons in gold containers.

### 5. 🍩 Curated Autumn Collection
* **Responsive 3-Column Grid**: Adapts dynamically from desktop to mobile screens using CSS Grid.
* **Interactive Cards**: Features custom badging (e.g., *"Best Seller"*, *"Signature"*, *"Seasonal"*), image-zoom hover effects, elegant gold borders, and floating interactive add-to-cart buttons.
* **Curated Delicacies**:
  1. **Parisian Macarons** ($24.00 / dozen)
  2. **Artisanal Chocolates** ($38.00 / 16 pcs)
  3. **Gourmet Cupcakes** ($18.00 / 6 pcs)
  4. **Classic Truffles** ($42.00 / 12 pcs)
  5. **Fruit Tarts** ($32.00 / 4 pcs)
  6. **Glacé Fruits** ($28.00 / gift jar)

### 6. 💬 "Sweet Words" Testimonials
* Soft-toned card blocks featuring elegant quotation marks and reviews from food curators, critics, and Michelin-starred chefs.

### 7. ✉️ Elegant Newsletter Subscription
* A modern subscription box asking users to join the exclusive **"Sweet Club"** for invitations to tasting events and seasonal releases.

### 8. 🤎 Rich & Informative Footer
* A dark chocolate background containing brand descriptions, social links with custom hover animations, detailed boutique hours, contact information, and elegant legal links.

---

## 🎨 Color Palette & Typography

The design utilizes a carefully selected color palette reflecting luxury, warmth, and culinary elegance:

| Element | Color Name | Hex Code | Visual Preview |
| :--- | :--- | :--- | :--- |
| **Primary Background** | Cream | `#FCF9F6` | <img src="https://via.placeholder.com/15/FCF9F6/000000?text=+" width="15" height="15" /> |
| **Secondary Accent** | Soft Blush Pink | `#F5E6E8` | <img src="https://via.placeholder.com/15/F5E6E8/000000?text=+" width="15" height="15" /> |
| **Card Background** | Elegant White | `#FFFFFF` | <img src="https://via.placeholder.com/15/FFFFFF/000000?text=+" width="15" height="15" /> |
| **Primary Accent** | Warm Gold | `#C5A880` | <img src="https://via.placeholder.com/15/C5A880/000000?text=+" width="15" height="15" /> |
| **Dark Gold Accent** | Brass / Ochre | `#A88F65` | <img src="https://via.placeholder.com/15/A88F65/000000?text=+" width="15" height="15" /> |
| **Main Text** | Deep Charcoal | `#2C2523` | <img src="https://via.placeholder.com/15/2C2523/000000?text=+" width="15" height="15" /> |
| **Heading Text** | Deep Chocolate | `#3D312A` | <img src="https://via.placeholder.com/15/3D312A/000000?text=+" width="15" height="15" /> |

### ✒️ Typography
* **Headings**: `'Playfair Display', serif` — Classic, luxurious, high contrast, and timeless.
* **Body Text**: `'Montserrat', sans-serif` — Clean, modern, highly legible, and stylish.

---

## 📂 File Structure

The project has been kept exceptionally clean, organized, and modular:

```bash
sweet-shop/
├── index.html        # Semantic markup, content structure, and mobile navigation script
└── styles.css        # Variables, keyframe animations, layouts, and responsive media queries
```

---

## 🚀 How to Run Locally

To view the website locally, you can serve it using a lightweight HTTP server. Since it consists of static files, any standard server will work perfectly.

### Method 1: Python HTTP Server (Recommended)
Python comes pre-installed on most systems. Run the following command in your terminal inside the `sweet-shop/` directory:

```bash
# Navigate to the directory
cd sweet-shop

# Start the server (on port 8081 or any available port)
python -m http.server 8081
```

Once started, open your favorite web browser and navigate to:
👉 **[http://localhost:8081](http://localhost:8081)**

---

## 📱 Responsiveness & Breakpoints

The website is fully optimized for all devices using responsive CSS media queries:

* **Desktops (`> 1024px`)**: Full 3-column collection grid, side-by-side split layouts, and horizontal navigation bar.
* **Tablets (`768px - 1024px`)**: 2-column collection grid, adjusted paddings, and collapsed margins.
* **Mobile Devices (`< 768px`)**: Single-column layout for collection cards and story sections, full-screen mobile menu drawer with hamburger toggle, and optimized typography sizes.

---

## 💎 Premium Design Touches
* **Custom Scrollbar**: A custom gold scrollbar (`::-webkit-scrollbar`) matching the shop's aesthetic.
* **CSS Variables**: Easy-to-manage colors, fonts, and transitions defined in `:root` for fast customization.
* **Hover Zoom Effects**: Smooth scale-up transitions on product images and social icons.
* **No-JS Smooth Scroll**: Native CSS smooth scrolling enabled for seamless navigation.

---

*La Douceur — Handcrafted with ❤️ and passion.*
