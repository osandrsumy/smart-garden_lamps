# Autonomous Smart Solar Lantern - Landing Page

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

High-converting, fully responsive landing page template optimized for modern e-commerce and retail sales of smart home/garden electronics. Specifically tailored for autonomous LED solar-powered motion-sensor outdoor lamps.

Designed for high performance, smooth mobile user experience (UX), and maximum sales conversion rates during emergency blackouts or seasonal garden preparation.

---

## 📱 Key Features

- **Blackout-Ready Focus:** Copywriting and UX elements target off-grid, energy-independent outdoor lighting features.
- **Ultra-Responsive Layout:** Optimized with custom grid styling explicitly calibrated for seamless performance on budget and mid-range mobile viewports (`width=480`).
- **Interactive Multi-Mode Selector:** Showcases 3 distinct operating modes (Motion Sensor, Eco + Sensor, Continuous Glow).
- **Custom Native JS Carousel:** A lightweight, vanilla JavaScript swipe-and-drag touch carousel for customer reviews with fallback keyboard navigation (`ArrowLeft` / `ArrowRight`) and native pointer capture API support.
- **Production Analytics Integrated:** Pre-equipped with standard high-performance Meta Pixel (`fbevents.js`) snippet for instant tracking of conversion metrics and page-view data.

---

## 🛠️ Project Structure & Tech Stack

The front-end design leverages modular style separation to maximize customization speed:

- **HTML5:** Clean, semantic structuring utilizing explicit layout blocks (`.main_wrapper`, `.offer_section`).
- **CSS3 / UI Customization:** Includes dynamic pulsing animations (`@-webkit-keyframes pulse`) to naturally direct consumer attention toward call-to-action (CTA) triggers without degrading processing performance.
- **Bootstrap Architecture:** Utilizes industry-standard utility wrappers paired with Owl Carousel configurations and Boxicons integration.
- **Vanilla JS Core:** Custom layout-independent logic handles state transformations and cross-platform drag triggers smoothly.

---

## 🚀 Quick Deployment Guide

To get this storefront up and running locally or host it on your production server, follow these simple steps:

Verify Asset Directories:
Ensure your root directory matches the following layout configuration:

├── index.html        # Main landing page markup (the provided source)
├── css/
│   ├── bootstrap.min.css
│   ├── style.css     # Main theme overwrites
│   └── animate.css   # Structural UI physics
├── js/
│   └── fbevents.js   # Production pixel engine
└── images/           # Compressed graphic assets (1.png, 2.png, etc.)
Configure Meta Pixel Integration:
Open index.html and replace the placeholder ID 2136718433808386 in the <script> tag with your active Meta Pixel tracking token.

Run Live:
Launch via any standard web server environment (NGINX, Apache) or quickly preview using VS Code's Live Server extension.

📈 Conversion Optimization
This page utilizes advanced frontend hooks built for conversion rate optimization (CRO):

Dynamic .discount badge calculations overlaid directly on top of raw imagery assets.

Smart aria-live="polite" accessibility announcements for continuous swipe monitoring.

Micro-gradient layout enhancements using strict modern fallback parameters (#FE4F17).

Developed as part of a high-performance open-source hardware distribution interface layout framework.
