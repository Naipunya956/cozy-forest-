# 🌲 Cozy Forest

A calming, gamified productivity app where every task you complete, habit you keep, and focus session you finish grows your own little magical forest.

Inspired by Studio Ghibli, Animal Crossing, and Stardew Valley — soft pastels, rounded corners, and zero corporate energy.

![status](https://img.shields.io/badge/status-active-4a7c59) ![license](https://img.shields.io/badge/license-MIT-87a878)

## ✨ Features

- **Tasks** — add, edit, complete, and delete tasks with categories, priority levels, and due dates. Completing one grows a tree and triggers a sparkle animation.
- **Habits** — track daily habits (study, workout, read, drink water, journal, and your own custom ones) with streak counters. Each completion blooms a flower.
- **Pomodoro Timer** — 25/5 focus sessions with an animated progress ring. Finishing a session adds sunlight to your forest.
- **Forest progression** — 10 unlockable levels, from a single sprout to a magical glowing tree, with grass, flowers, a river, a bridge, mushrooms, rabbits, a fox, and deer along the way.
- **Shop** — spend coins earned from productivity on lanterns, benches, a campfire, fairy lights, and more decorations for your forest.
- **Journal** — daily mood tracker, gratitude list, and an AI "Forest Spirit" companion that reflects on your entries.
- **Forest Spirit AI companion** — a friendly chat widget that encourages you, helps prioritize tasks, and celebrates your wins.
- **Stats & achievements** — track tasks completed, focus minutes, streaks, and unlock badges.
- **Dark mode**, sound/animation toggles, and full mobile responsiveness.
- **Local-first data** — everything saves automatically to your browser. Includes export/import buttons to back up or move your data between devices.

## 🛠️ Tech

Built as a single self-contained `index.html` file — no build step, no install, no server required.

- Vanilla HTML / CSS / JavaScript
- `localStorage` for persistence
- CSS animations + keyframes for the forest's living feel (swaying trees, floating leaves, fireflies, birds, weather)

> The original architecture plan (see `/docs`) was scoped for a React + TypeScript + Tailwind + Firebase stack for a production version with multi-device cloud sync. The current build is a fully working single-file prototype implementing all the same features client-side.

## 🚀 Getting started

No installation needed.

1. Clone or download this repo
2. Open `index.html` in any modern browser
3. Start adding tasks — your forest starts growing immediately

```bash
git clone https://github.com/YOUR-USERNAME/cozy-forest.git
cd cozy-forest
open index.html   # or just double-click the file
```

## 💾 Data & backups

Your tasks, habits, journal entries, and forest progress are saved in your browser's local storage automatically, and persist indefinitely unless you clear your browser data. Since there's no server or account, your data lives only on the device/browser you use it on.

To move your forest to another device or keep a backup, use **Settings → Export backup**, which downloads a `.json` snapshot you can later restore with **Settings → Import backup**.

## 🗺️ Roadmap

- [ ] Migrate to React + TypeScript + Vite for component-based architecture
- [ ] Add Supabase/Firebase backend for cross-device sync and accounts
- [ ] Real AI integration (Claude API) for the Forest Spirit, goal breakdown, and journal summaries
- [ ] Ambient sound design (forest, rain, lo-fi music)
- [ ] Drag-and-drop forest decoration placement
- [ ] PWA support for offline installs on mobile

## 📄 License

MIT — use it, fork it, build on it.

## 🎬 Demo



