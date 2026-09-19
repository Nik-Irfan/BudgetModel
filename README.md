# Budget Model — Budget, beautifully.

[[Version](https://img.shields.io/badge/version-1.6.1-black?style=flat-square)](https://github.com/YOURUSERNAME/budget-model)
[[Mobile First](https://img.shields.io/badge/mobile--first-100%2F100-brightgreen?style=flat-square)](#)
[[No Tracking](https://img.shields.io/badge/privacy-local--only-blue?style=flat-square)](#)
[[License: MIT](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)](LICENSE)
[[GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-black?style=flat-square&logo=github)](https://YOURUSERNAME.github.io/budget-model/)

A clean, minimalist, premium budgeting app that feels like Apple Wallet. Built for Malaysians — split your salary into pots like **Maybank, AEON, Tabung Haji** and track what's left without the stress.

**Live demo:** https://YOURUSERNAME.github.io/budget-model/

> **Budget first, details on demand.** Dashboard shows only your budgets. Tap a pot to see expenses.

---

### ✨ Why this one?

- **Not scary:** No charts, no jargon. Just "RM 1,450 left" in big type.
- **Thumb-friendly:** All actions at bottom, 56px buttons, single-hand use.
- **Fast:** Single HTML file, works offline, localStorage only — no login, no tracking.
- **Real Malaysian flow:** RM currency, after-EPF mindset, pot names you actually use.

### 📱 Features (v1.6.1 Final)

- **Salary input** with auto RM formatting and cursor fix
- **Models:** 50/30/20, 80/10/10, **Custom builder** (all 6 colors)
- **Name your pots:** Maybank for 50%, AEON for 30%, etc.
- **Dropdown dashboard:** Collapsed by default, tap to expand
- **Expense CRUD:** Add item + RM amount per pot, shows `RM X over` in red when over-budget
- **Sharing:** Proper OG tags for WhatsApp / Telegram — fixed "React Artifact" bug

### 🚀 Quick Start

```bash
npm install
npm run dev      # http://localhost:5173 + Network URL
npm run build && npm run preview
```

**GitHub Pages (single file):**
1. Rename `budget-model-standalone.html` to `index.html`
2. Push to main
3. Settings > Pages > Deploy from main/root

### 🔗 WhatsApp Sharing Fix (v1.6.1)

If WhatsApp still shows "React Artifact":
1. Push fixed index.html with OG tags
2. Bust cache: https://developers.facebook.com/tools/debug/ -> paste URL -> Scrape Again x2
3. Or share with ?v=2 for fresh preview

### 🧪 QA Status

Desktop 100/100, Mobile 100/100, 0px overflow. Publish ready.

### 🛠️ Stack

React 18 + TypeScript + Tailwind + Vite. 100% localStorage.

### 🔒 Privacy

100% local. No analytics.

### 📝 Changelog

- v1.6.1 - Fix OG tags for WhatsApp, fix tab title in static HTML
- v1.6 - Final publish-ready bug fixes
- v1.4 - Edit pencil icon, collapsed dashboard

**Made in Kota Kinabalu, Sabah.** Star ⭐ if it helped!
