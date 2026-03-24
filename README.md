# 🌾 KisanAI — The Farmer's Smart Companion

> "Ask AI → Get Advice. Check Market → Sell Smart. Track Farm → Grow Better."

---

## ✨ Features

- 🏠 **Home** — Bilingual hero (Hindi/English), weather strip, quick stats
- 🤖 **AI Crop Advisor** — Claude-powered chat with severity badges, symptom chips, diary save
- 📈 **Market Prices** — Real-like mandi prices for 12 crops across 3 states, trend indicators
- 📋 **Govt Schemes** — 6 schemes with eligibility filter (land size, state, crop type)
- 🌦️ **Weather & Tips** — 5-day forecast + rotating daily farming tips

---


> ⚠️ **AI Advisor Note:** The Claude API call goes through the Anthropic proxy (no API key needed in the client when run via Claude.ai artifact). For standalone use, add your `ANTHROPIC_API_KEY` or proxy the API calls through your own backend.

---

## 🗂️ File Structure

```
kisanai/
├── index.html              # Entry HTML
├── package.json            # Dependencies
├── vite.config.js          # Vite setup
├── tailwind.config.js      # Tailwind config
├── postcss.config.js       # PostCSS
└── src/
    ├── main.jsx            # React root mount
    ├── App.jsx             # Full app (all screens + components)
    └── index.css           # Tailwind + global styles
```

---

## 🎨 Design System

| Token | Color | Usage |
|-------|-------|-------|
| Primary | `#2D6A4F` | Headers, nav active |
| Secondary | `#74C69D` | Buttons, interactive |
| Accent | `#F4A261` | CTAs, badges |
| Background | `#F8F5F0` | Page background |

**Fonts:** Poppins (headings) + Inter (body)

---


