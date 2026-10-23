# FORM 8 — Personal Fitness Tracker

A mobile-first installable Progressive Web App for an 8-week fitness plan. Designed for iPhone Safari and modern browsers.

## Features
- Overview dashboard with weight, waist, protein, steps, daily habits and workout preview.
- Weekly plan: three beginner strength sessions, walking/cardio and recovery days.
- Exercise checklist and session completion log.
- Food diary with calories and protein, Nepali-friendly quick-add foods, and configurable protein target.
- Weight and waist check-ins, SVG weight trend chart, 8-week milestone roadmap, and history.
- Progress photos compressed in-browser and stored locally.
- JSON export backup, local-only persistence, responsive iOS-friendly UI, offline cache after first visit.

## Install on iPhone
1. Open the deployed site in **Safari** on your iPhone.
2. Tap **Share → Add to Home Screen** and enable **Open as Web App** if offered.
3. Launch FORM 8 from your Home Screen. Open it online once so app assets are cached for offline use.

## Local run
From this directory run `python3 -m http.server 8080` and open `http://localhost:8080`.

## Data & privacy
No account, analytics, API or cloud sync is configured. Logs and photos are stored in browser local storage on this device. Clearing website data can erase them. Use **Progress → Export data** to back up JSON regularly. The app does not sync between devices.

## Personal defaults
- Starting weight: 68 kg
- Goal weight: 60 kg
- Height: 170 cm
- Daily protein target: 120 g
- Step target: 8,000
- Estimated calorie range: 1,800–2,000 kcal/day, adjusted based on actual progress and recovery.

These are planning estimates, not medical advice. Avoid crash dieting; adjust targets according to energy, hunger and training performance.
