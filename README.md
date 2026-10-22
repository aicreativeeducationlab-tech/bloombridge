# 🌸 BloomBridge

A co-parenting companion web app — one shared space for the grown-ups and a safe, playful space for the kids.

**Live demo:** https://bloombridgekid.netlify.app

## What it does

**For parents & guardians**
- 👥 Family Access Codes — relatives join by code, no accounts to manage
- ☁️ Real-time cloud sync (Firebase) — log a meal on your phone, it appears on theirs
- ⏱️ 1-tap care logging — meals, meds, naps, play, and more
- 🏠 Three family modes: **Under One Roof**, **Two Homes One Team**, **Court-Guided** (permanent, precisely-timestamped records)
- 📅 Calendar & events with day detail, categories, and photos
- 💖 One-tap thank-you notes — co-parenting runs on kindness
- 🔥 Logging streaks with milestone celebrations
- 🌟 Star jar — award stars for awesome behavior
- 📦 Invite files & cloud backup

**For kids (Kid Code login only — parents can't enter)**
- 💬 "I Want…" talk board — 16 picture cards; one tap speaks the sentence aloud and notifies the grown-ups (AAC-friendly)
- 🎀 Doll Studio, games, speed dial & walkie-talkie voice notes
- 🌟 A star jar that fills up as they earn stars

## Tech

- Single-file app: HTML + CSS (Tailwind) + React (via CDN) + Babel
- Firebase (Firestore + Anonymous Auth) for real-time multi-device sync
- Zero build step — open `index.html` or drop the file on Netlify

## Run it

Just open `index.html` in a browser, or deploy to Netlify Drop. No install, no build.

## License

MIT
