# ⏰ Clocky – Multi-Device Web App

Clocky is a mobile-first web application with:

- **Alarm(s)** (with notification + chime, multiple alarms supported)
- **Stopwatch** (with laps)
- **Timer** (with notification + chime)
- **Weather** (powered by [Open-Meteo API](https://open-meteo.com/), free & no key required)

---

## 📂 Files Overview

- **`index.html`** → Redirector (auto-detects iOS/Android, falls back to chooser).
- **`index-android.html`** → Android version  
  - Portrait upright → Alarm  
  - Landscape right → Stopwatch + Weather  
  - Portrait upside down → Timer (if supported)  
  - Fallback Timer button always available  

- **`index-iOS.html`** → iOS version  
  - Portrait upright → Alarm  
  - Landscape left → Stopwatch + Weather  
  - Landscape right → Timer  

- **`choose.html`** → Manual chooser (lets the user select Android or iOS manually).  

---

## 🚀 Deployment on GitHub Pages

1. Upload all files (`index.html`, `index-android.html`, `index-iOS.html`, `choose.html`) to your GitHub repo root.
2. In your repo → **Settings → Pages**  
   - Source: `Deploy from branch`  
   - Branch: `main` (or your default)  
   - Folder: `/ (root)`  
3. Save.  
4. Open:  
