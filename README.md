# hz

A simple, no-nonsense web app for restorative audio therapy

>[!IMPORTANT]
> iOS currently has no working audio. Android status is currently unknown. Please drop anything in a discussion or issue. I'll be working on it.

> [!NOTE]
> This app is currently in development and may not work as expected.
> If you find any issues, please report them in the issues section.

> [!TIP]
> Yes, this is the repo from zakdev12312, it's been migrated over from there.


## What it does

- **Restorative Tone**: Deep, pure sine wave tones (20-100Hz) with a timer (30s, 1min, or 5min). Think grounding, low-frequency sound.
- **Brown Noise**: A deep, airplane-cabin-style rumble that plays indefinitely. No timer, just continuous soothing noise.

Features:
- Switch between tone and brown noise modes
- Adjustable timer presets for the tone
- Reset button to restart the timer
- Light/dark mode toggle (your preference is saved)
- Works entirely in your browser - no downloads, no accounts

## Run it locally

Option 1: Download ZIP
1. Download this repo as a ZIP and extract it
2. Open a terminal and `cd` into the folder
3. Run `npm install` then `npm run dev`

Option 2: Git Clone
```bash
git clone https://github.com/zakdev12312/hz.git
cd hz
npm install
npm run dev
```

Then open `http://localhost:5173/hz` in your browser.

---

© 2025 zakdev12312. Licensed under the MIT license.

