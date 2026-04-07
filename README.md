# STK Camera — Landing Page

Official GitHub Pages landing page for **STK Camera**, a mobile app that reads Soil Test Kit (STK) color strips using CIEDE2000 color matching and Claude Vision AI.

🌐 **Live site:** https://phpthinky.github.io/stk-camera-mobile*(update once deployed)*

---

## About the App

STK Camera is a field-ready soil analyzer built for agriculture students, farm technicians, and researchers. Point your camera at any standard soil test kit strip and instantly get pH, Nitrogen, Phosphorus, and Potassium readings — no internet required for core analysis.

Built under the **TAM (Tech-Agri for Mindoro)** ecosystem by [@phpthinky](https://github.com/phpthinky), Sablayan, Occidental Mindoro 🇵🇭

---

## Tech Stack (App)

- **Framework:** Laravel + NativePHP (Android)
- **Color Engine:** CIEDE2000 algorithm
- **AI Layer:** Claude Vision API
- **Database:** SQLite (offline-first)
- **Credits System:** Token-based, GCash top-up

---

## Landing Page Structure

```
index.html        ← Single-file landing page (pure HTML/CSS/JS)
README.md         ← This file
```

No build tools. No dependencies. Just drop `index.html` and deploy.

---

## Deploy to GitHub Pages

1. Push `index.html` to your repo's `main` branch
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Save — live in ~60 seconds

---

## Update Checklist

Before going live, update these in `index.html`:

- [ ] Google Play Store URL in the Download buttons
- [ ] Contact email in footer
- [ ] Credits top-up pricing (once finalized)
- [ ] App screenshots (replace phone mockup when ready)

---

## Related Repos

| Repo | Description |
|---|---|
| `stkcamera-mobile` | NativePHP Android app |
| `wood-identifier-mobile` | Wood species identifier app |
| `mobile-gis-leaflet-plugin` | Custom NativePHP GIS plugin |

---

## License

© 2026 phpthinky. All rights reserved.
