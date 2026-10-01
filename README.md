# 🪙 Cara ou Coroa Virtual

> **Live site:** [caraoucoroavirtual.com](https://caraoucoroavirtual.com)

A free, no-ads, no-signup virtual coin flip simulator built for Brazilian Portuguese speakers — and anyone who needs a fast, fair decision-maker.

## 💡 What It Does

**Cara ou Coroa Virtual** helps you make instant, unbiased decisions by simulating a coin toss right in your browser. No physical coin needed — just click and flip.

Whether you're settling a debate with friends, picking who goes first in a game, running a classroom probability experiment, or simply can't decide what to eat for lunch, this tool gives you a truly random 50/50 result in under 2 seconds — with a satisfying 3D animation and real coin sound.

### ✨ Key Features

- **3D Coin Animation** — Realistic CSS 3D flip with metallic gold (cara) and silver (coroa) faces, landing with a satisfying bounce
- **Live Statistics** — Tracks counts, percentages, current streak, and longest streak in real time
- **Multi-Coin Mode** — Flip 2–5 coins simultaneously for group votes or majority decisions
- **Best-of Tournaments** — Play Best of 3, 5, or 7 — the first side to reach majority wins, with a confetti celebration
- **Custom Labels** — Replace "Cara / Coroa" with anything: "Sim / Não", "Pizza / Sushi", "Home / Away"
- **Sound & Haptics** — Real coin sound effect + haptic feedback on compatible Android devices
- **Dark Mode** — Toggle between light and dark themes
- **Keyboard Shortcuts** — `Space` to flip, `R` to reset — no mouse needed
- **Zero Data Collection** — No cookies, no tracking, no accounts. Results live only in your browser's memory

## 🚀 Running Locally

```sh
npm install
npm run dev
```

Dev server starts at `http://localhost:4321`

## 🧞 Commands

All commands are run from the root of the project:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## 🛠️ Built With

- [Astro](https://astro.build) — Static site framework
- Tailwind CSS v4 — Styling
- Vanilla JavaScript — Coin physics, animations, and game logic
- Cloudflare Pages — Hosting & CDN
