# 🦒 Type Safari

A fun, offline typing tutor for kids, built for **Start Point Academy** (Tanzania).

Kids learn to touch-type by following **Twiga the giraffe** on a journey across Tanzania — 16 stops that weave in geography, history, and civics (Kilimanjaro, Serengeti, Zanzibar, Kilwa, Uhuru 1961, Mwalimu Nyerere, the flag, the anthem, and more). Each stop teaches a piece of the keyboard (home row → all letters → capitals → punctuation → numbers → sentences) and unlocks its own Tanzanian-themed mini-game as a reward.

## Features
- 16 progressive lessons, beginner → proficient, in the spirit of Mavis Beacon.
- Live words-per-minute, accuracy, and error count; a full on-screen laptop keyboard with finger-colour guidance and Shift hints.
- 16 themed mini-games (one per stop) — Cargo Catch, Climb Kilimanjaro, Migration Race, Catch the Sato, Paint the Flag, Uhuru Fireworks, and more.
- Name-based profiles for multiple children, saved on the device.
- Works **fully offline** and installs as an app (PWA). No accounts, no internet needed for kids.
- Content is English-first with Kiswahili words sprinkled in.

## Run it locally
Just open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari). It works offline.

## Deploy with GitHub Pages
1. Push this folder to a GitHub repository (see steps below).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Branch: **main**, folder: **/ (root)**. Click **Save**.
5. After a minute, your site is live at `https://<your-username>.github.io/<repo-name>/`.
6. Open that link in Chrome/Edge and click **⬇ Install app** to install it on each computer. After the first visit it runs offline.

## Tech
A single static `index.html` (HTML/CSS/JavaScript, no build step, no dependencies), plus a web manifest, a service worker for offline use, and PNG icons. Nothing to compile — no Node or npm required.

---
© Start Point Academy. Made for Tanzanian learners. 🇹🇿
