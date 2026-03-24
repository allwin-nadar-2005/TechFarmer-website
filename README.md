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

## 🚀 HOW TO RUN

### Step 1 — Install dependencies
```bash
npm install
```

### Step 2 — Start dev server
```bash
npm run dev
```

### Step 3 — Open in browser
```
http://localhost:5173
```

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

## 🏆 5-Line Pitch

KisanAI solves the #1 pain of India's 140M small farmers: no single, trusted source for crop advice, market prices, and government scheme information — all in their language, on any phone.

It's built for farmers like Ramesh (2 acres, wheat grower in UP) who lose ₹20,000+ per season from pest damage, wrong timing, and missed subsidies — simply from lack of accessible information.

It works as a mobile-first web app with 5 screens: an AI chat advisor powered by Claude (Hinglish responses with severity-rated remedies), live-like mandi prices with buy/sell signals, and a smart scheme matcher that filters PM Kisan, Fasal Bima, and 4 others by land size and crop type.

Unlike agri-portals that are desktop-only, English-heavy, and never answered a real question — KisanAI speaks the farmer's language, literally and visually, with bilingual UI, 48px tap targets, and a chat interface that even low-literacy users can navigate.

We built this in under 60 minutes as a working prototype — and with real API integration + offline support, it can reach 50M farmers in 6 months. **Jai Kisan. 🙏**
