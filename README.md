# www-specialized-skin-care-clinic.et
# 🏥 Dr. Feyza Seid — Specialized Skin Care Clinic Website

A modern, responsive, multi-language landing page for **Dr. Feyza Seid Specialized Skin Care Clinic** based in Bahir Dar, Ethiopia.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Pages & Sections](#pages--sections)
- [Tech Stack](#tech-stack)
- [File Structure](#file-structure)
- [Setup & Deployment](#setup--deployment)
- [Customization Guide](#customization-guide)
- [Language Support](#language-support)
- [Contact & Credits](#contact--credits)

---

## Overview

This is a single-file HTML website built for Dr. Feyza Seid's dermatology and skin care clinic. It is designed to attract new patients, showcase clinic services, provide contact information, and enable easy appointment booking — all in a clean, professional, mobile-friendly design.

**Live Booking URL:** https://specialized-skin-care-clinic.onrender.com

---

## ✨ Features

| Feature | Description |
|---|---|
| 🌐 **130+ Language Translator** | Powered by Google Translate — one click translates the entire site |
| 📱 **Fully Responsive** | Works perfectly on mobile, tablet, and desktop |
| 💬 **WhatsApp Float Button** | Pulsing WhatsApp chat button fixed to the bottom-right corner |
| 📍 **Contact Details** | Address, phone, WhatsApp, and online booking link |
| 🕐 **Opening Hours** | Clear weekly schedule displayed in the contact section |
| 📖 **About Section** | Clinic story, values, and team introduction |
| 🧴 **Services Grid** | Six specialized service cards with icons |
| 📊 **Stats Banner** | Animated key numbers (5000+ patients, 98% satisfaction, etc.) |
| 📲 **Social Media Links** | Instagram, TikTok, Telegram, and WhatsApp follow buttons |
| 🎨 **Dark Mode Ready** | CSS variables set up for easy dark theme toggling |
| ⚡ **Scroll Animations** | Stats section animates into view on scroll |
| 🔗 **Smooth Scroll Nav** | Navigation links scroll smoothly to each section |

---

## 📄 Pages & Sections

The site is a single-page application (`skin_clinic.html`) with the following sections:

1. **Header / Navigation** — Sticky top bar with logo, nav links, and language switcher
2. **Hero** — Full-height welcome banner with headline, description, and CTA buttons
3. **About** — Two-column section with clinic photo and story text
4. **Services** — Six-card grid of specialized dermatology services
5. **Stats** — Animated statistics strip (patients, satisfaction rate, support, personalized care)
6. **Opening Hours & Contact** — Hours table + contact card with address, phone, WhatsApp
7. **Follow Us** — Social media section with platform buttons
8. **CTA** — Call-to-action banner linking to the booking system
9. **Footer** — Links, clinic info, and developer credits

---

## 🛠 Tech Stack

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties (variables), Flexbox, Grid, animations
- **Vanilla JavaScript** — Smooth scroll, scroll-triggered animations
- **Google Fonts** — `Cormorant Garamond` (headings) + `DM Sans` (body)
- **Google Translate API** — Free widget supporting 130+ languages
- **No frameworks. No build tools. No dependencies.**

---

## 📁 File Structure

```
/
├── skin_clinic.html      # Main website (single file — everything included)
└── README.md             # This documentation file
```

All CSS, JavaScript, and HTML are contained in one file for easy deployment.

---

## 🚀 Setup & Deployment

### Option 1 — Open Locally
Simply double-click `skin_clinic.html` in your file explorer. It will open in your default browser.

> **Note:** The Google Translate widget requires an internet connection to function.

### Option 2 — Deploy to Render (recommended)
1. Create a free account at [render.com](https://render.com)
2. Create a new **Static Site**
3. Upload or link your GitHub repo containing `skin_clinic.html`
4. Set the **Publish Directory** to `/` (root)
5. Set `skin_clinic.html` as the root document
6. Deploy — your site is live!

### Option 3 — GitHub Pages
1. Push the file to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to the `main` branch, root folder
4. Rename `skin_clinic.html` to `index.html`
5. Your site is live at `https://yourusername.github.io/repo-name`

### Option 4 — Any Web Host
Upload `skin_clinic.html` (rename to `index.html`) to any hosting provider's `public_html` or `www` folder via FTP or cPanel File Manager.

---

## 🎨 Customization Guide

### Update Contact Information
Open `skin_clinic.html` and search for:

```html
Bahir Dar, Nock Building<br>Floor G+2, Room xx
```
Replace `Room xx` with the actual room number.

```html
+251 (0) 9xxxxx
```
Replace with the real phone number. Update **all three instances** (contact card, WhatsApp button, footer).

### Update WhatsApp Number
Search for `wa.me/2510975882230` and replace `2510975882230` with the correct number in international format (no `+`, no spaces). Example: Ethiopia +251 912 345 678 → `2510912345678`.

### Update Social Media Links
Find each social button and replace the `href`:

```html
<!-- Instagram -->
<a href="https://www.instagram.com/YOUR_HANDLE" ...>

<!-- TikTok -->
<a href="https://www.tiktok.com/@YOUR_HANDLE" ...>

<!-- Telegram -->
<a href="https://t.me/YOUR_CHANNEL" ...>
```

### Update Opening Hours
Find the `.hours-row` elements in the Hours section and edit the time values:

```html
<div class="hours-row">
  <span class="day">Monday</span>
  <span class="time">8:00 – 13:00</span>   ← change this
</div>
```

### Change Brand Colors
All colors are defined as CSS variables at the top of the `<style>` block:

```css
:root {
  --sky: #0284c7;        /* Primary blue */
  --sky-light: #0ea5e9;  /* Lighter blue for gradients */
  --sky-dark: #0369a1;   /* Darker blue for hover states */
  --navy: #0f172a;       /* Dark text / headings */
}
```

### Replace Hero Image
Find the `<img>` tag inside `.hero-image` and replace the `src` URL with your own image:

```html
<img src="YOUR_IMAGE_URL_HERE" alt="Skincare">
```

### Replace About Section Image
Find the `<img>` tag inside `.about-img` and update the `src`.

---

## 🌐 Language Support

The website uses the **Google Translate Widget** to support **130+ languages**, including:

| Region | Languages |
|---|---|
| East Africa | Amharic 🇪🇹, Somali, Swahili, Oromo, Tigrinya |
| Middle East | Arabic, Hebrew, Persian, Turkish |
| Europe | English, French, German, Spanish, Italian, Portuguese, Russian, Dutch |
| Asia | Chinese (Simplified/Traditional), Japanese, Korean, Hindi, Bengali |
| And many more... | All languages supported by Google Translate |

The translate button appears in the header navigation bar. Clicking it opens a dropdown — users select their language and the entire page is instantly translated.

**RTL (Right-to-Left) languages** like Arabic are automatically handled by the Google Translate widget.

---

## 📞 Contact & Credits

### Clinic
**Dr. Feyza Seid Specialized Skin Care Clinic**
📍 Bahir Dar, Nock Building, Floor G+2, Room xx
📞 +251 (0) 9xxxxx
🌐 https://specialized-skin-care-clinic.onrender.com

### Developer
**Asmamaw Yehun**
Ph.D & Certified Software Engineer

- ✉️ chanieasmamaw@yahoo.com
- 🔗 [linkedin.com/in/asmamaw-chanie-yehun](https://www.linkedin.com/in/asmamaw-chanie-yehun)
- 📞 0975882230

---

## 📜 License

© 2026 Dr. Feyza Seid Specialized Skin Care Clinic. All rights reserved.

This website was custom-built for Dr. Feyza Seid's clinic. Redistribution or reuse of this code for other clinics or commercial purposes requires permission from the developer.