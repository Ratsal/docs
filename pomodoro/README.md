# 🟠 Rajipo Time — Sci-Fi Focus Timer

A single-file focus timer that runs in any browser. No installs, no accounts, no build step.

## Features
- Futuristic sci-fi orange theme (cool cyan during breaks)
- Configurable focus length (1 / 2 / 5 / 10 / 15 / 20 / 25 min, or custom)
- Short breaks between sessions (Off / 1 / 2 / 5 min) on their own distinct screen
- **Auto-loop** — focus → short break → focus, continuously
- Choose your alarm sound (tap to preview): 🐦 Birds, 💎 Crystal, 🌌 Cosmic — all generated live, no audio files
- Distraction-free focus mode: menus hide while running; ✕ Exit (top-left) and ⚙ Settings (top-right)
- Pause / resume, optional screen flash on alarm
- Daily completed-session counter (saved on your device, resets each day)
- Add to your iPhone home screen for a full-screen, app-like experience

## How to use it on your phone
1. Open the hosted link in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Launch it from the new icon — it opens full-screen like an app.

> **iPhone note:** the alarm sounds and animates while the screen is on and the
> app is open. iPhone (Safari) does **not** allow web apps to vibrate or to ring
> while the phone is locked — that requires a native iOS app.

## Hosting it for free (GitHub Pages)
1. In this repo on GitHub: **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Pick the branch this lives on and folder **/ (root)**, then **Save**.
4. After a minute your timer is live at:
   `https://<your-username>.github.io/<repo>/pomodoro/`

## Running it locally
Just open `pomodoro/index.html` in any browser — it's fully self-contained.
