# ⏱️ Focus Loop — Pomodoro Timer

A single-file focus timer that runs in any browser. No installs, no accounts, no build step.

## Features
- Configurable session length (10 / 15 / 20 / 25 min, or a custom number)
- **Auto-continue** — automatically rolls into the next session
- Pause / resume / reset
- Pick what happens when a session ends:
  - 🔔 alarm sound
  - ✨ screen flash
  - 📣 keep ringing until you tap
- Optional 5-minute breaks between sessions
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
