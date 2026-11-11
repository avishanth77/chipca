# Chipca — The Good Bite 🍌✨

Authentic, handcrafted Kerala chips inspired by traditional recipes and packed to stay crisp.

An interactive, responsive 3D web experience built with **Three.js**, dynamic theme transitions, product showcase, and a direct **WhatsApp ordering system**.

---

## 🌟 Features

- **Interactive 3D Hero Carousel (Page 1):** Real-time 3D rotating chip packets with dynamic color-adaptive backdrops, flavor ink transitions, and dual touch/pointer navigation.
- **Flavour Showcase (Page 2):** High-definition packet carousel with custom nutritional benefit icons, realistic ground contact shadows, keyboard arrow navigation, and mobile swipe gestures.
- **Our Craft Story (Page 3):** Three-stage craft storytelling (*Sliced Thin*, *Fried in Small Batches*, *Packed to Stay Crisp*).
- **Online Shop & WhatsApp Cart (Page 4):**
  - Responsive cards for all 5 signature flavours (*Classic Banana*, *Robusta Banana*, *Heritage Taro*, *Malabar Masala*, *Single Stick Cut*).
  - Quantity steppers (`-` / `+`) with animated "Added" feedback.
  - Floating translucent glassmorphic shopping cart button with live badge counter.
  - Slide-in cart drawer with delivery details form and one-click WhatsApp order generation directly to `+91 8075555456`.
- **Custom Brand Footer (Page 5):**
  - Double-layered organic curved wave divider (amber ribbon & roasted espresso).
  - Brand wordmark with golden smile swoosh underline.
  - Quick links, customer support & bulk inquiry triggers.
  - Interactive newsletter subscription pill form.
  - Social media and legal terms links.
- **Search & AI Optimization (AEO / GEO):**
  - Schema.org JSON-LD structured data graph (`Organization`, `WebSite`, `BreadcrumbList`, `Product` schemas with AggregateOffers, and `FAQPage`).
  - Search crawler directives via `robots.txt` and XML image `sitemap.xml`.
  - Accessible, on-page FAQ accordion section for AI citation engines.

---

## 🚀 Live Demo / Pages

Open [`index.html`](index.html) or host on GitHub Pages:
`https://avishanth77.github.io/chipca/`

---

## 📁 Project Structure

```
├── index.html                           # Main entry point (Production website)
├── robots.txt                           # Search & AI crawler directives
├── sitemap.xml                          # XML Sitemap with Google image extensions
├── README.md                            # Documentation
├── CHAT_HISTORY.md                      # Complete turn-by-turn development log
├── .gitignore                           # Git ignore configuration
│
├── assets/                              # Consolidated static assets
│   ├── images/
│   │   ├── products/                    # High-res packet cutouts (PNG & WebP)
│   │   │   ├── classic.png / .webp
│   │   │   ├── robusta.png / .webp
│   │   │   ├── taro.png / .webp
│   │   │   ├── masala.png / .webp
│   │   │   └── stick.png / .webp
│   │   └── branding/                    # Brand wordmark and logos
│   │       ├── chipca_logo_white.png / .webp
│   │       └── chipca_logo_dark.png / .webp
│   ├── icons/                           # 14 Nutritional & flavour benefit icons
│   │   ├── 100_coconut_oil.png
│   │   ├── 100_natural_spices.png
│   │   ├── artisanal_matchstick_cut.png
│   │   └── ...
│   └── burst/                           # Burst animation SVG rays & config
│       ├── burst-config.js
│       ├── burst-config.json
│       ├── classic/
│       ├── robusta/
│       ├── taro/
│       ├── masala/
│       └── single/
│
└── archive/                             # Archived and reference files
    ├── demos/                           # Interactive 3D & burst reference demos
    │   ├── Chipca Classic Chips – 3D Spin (1).html
    │   ├── chipca_animation.html
    │   └── ...
    └── legacy/                          # Earlier version site backups
        ├── hero.html
        ├── Chipca site 1.html
        └── Chipca site 1.original.html
```

---

© 2026 Chipca Foods. All rights reserved.
