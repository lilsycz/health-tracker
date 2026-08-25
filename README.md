# Health Tracker PWA

A personal health tracking Progressive Web App built with React, deployed on GitHub Pages with Google Sheets sync.

🔗 **Live Demo**: [lilsycz.github.io/health-tracker](https://lilsycz.github.io/health-tracker/)

---

## Features

- **Training Log** — Track workouts across A/B/C day splits with set-by-set checkboxes; separate cardio tab
- **Meal Tracking** — Per-ingredient nutrition calculation with fixed breakfast and snack modules
- **Google Sheets Sync** — Data syncs to a personal Google Sheet via Apps Script webhook
- **PWA Support** — Installable on mobile, works offline
- **Auto Reset** — Daily records reset automatically at midnight

---

## Tech Stack

- React (Vite)
- localStorage for persistence
- Google Apps Script (Sheets webhook)
- GitHub Actions for CI/CD
- GitHub Pages for hosting

---

## Known Issues

- iOS Safari may cache a stale Service Worker — fix by clearing site data in Safari settings and hard-refreshing

---

## Local Development

```bash
npm install
npm run dev
```

---

## Deployment

Automatically deployed to GitHub Pages via GitHub Actions on push to `main`.

```bash
npm run build
```
