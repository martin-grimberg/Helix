# Helix 🌙

**Put your phone down before bed. Earn real rewards.**

Helix is a web app that turns the "5 more minutes" scrolling habit into an incentive to stop. Users set their bedtime, start a wind-down timer and put the phone away. Every minute spent outside the app earns **Lunas**, a currency that unlocks real discounts on wellness products such as yoga mats, teas and sleep gear.

🔗 **Live demo:** [martin-grimberg.github.io/Helix](https://martin-grimberg.github.io/Helix/)

> Built as a social venture in the **Heseg Foundation Impact Entrepreneurship Track** (2025–2026), a zero-to-one program for lone-soldier scholars building ventures around real unmet needs. Presented at **Demo Day 2026**.

---

## The problem

- 62% of people worldwide don't get enough sleep *(Philips Global Sleep Survey)*
- One hour of phone use before bed suppresses melatonin for about 3 hours *(Harvard Medical School)*
- Average daily screen time for teens is 7+ hours *(Common Sense Media)*

Everyone knows they should stop scrolling. Nothing is at stake if they don't. Helix doesn't try to change the user; it changes the incentive.

## How it works

1. **Set your bedtime.** Helix calculates your wind-down window.
2. **Start the timer.** One tap starts the countdown, then the phone goes down.
3. **Stay offline.** Helix tracks whether you leave the app. Every minute of wind-down earns Lunas.
4. **Redeem rewards.** Spend Lunas in the Wellness Shop on discounts from partner brands.

## Features

- **Home:** bedtime setup and the wind-down timer
- **Shop:** wellness marketplace where Lunas are redeemed
- **Stats:** sleep-habit history and progress
- **Profile:** user settings and balance
- **Anti-cheat integrity tracking:** uses page-visibility tracking to detect when the user leaves the app during a session, so Lunas are only earned for real time offline

## Tech stack

- [React](https://react.dev/) 19 + [Vite](https://vite.dev/)
- [Recharts](https://recharts.org/) for the Stats charts, [Lucide](https://lucide.dev/) for icons
- JavaScript, ESLint
- Deployed with GitHub Pages ([gh-pages](https://www.npmjs.com/package/gh-pages))

## Run locally

```bash
git clone https://github.com/martin-grimberg/Helix.git
cd Helix
npm install
npm run dev
```

Build for production:

```bash
npm run build
```

Deploy to GitHub Pages (builds first, then publishes `dist/`):

```bash
npm run deploy
```

## Status and roadmap

Pre-launch: a working prototype, market research (17 competitors mapped) and a business model (B2B brand partnerships + freemium subscription).

| Phase | Timeline | Goal |
| --- | --- | --- |
| 1 | Q3–Q4 2026 | Israel launch, App Store + Play Store submission |
| 2 | Q1–Q2 2027 | English markets (US + UK), premium tier |
| 3 | Q3–Q4 2027 | Spanish-language rollout (LATAM) |

## Team

| Name | Role |
| --- | --- |
| Roni Goren | Co-CEO: vision, product strategy, stakeholder relations |
| **Martin Grimberg** | **CTO: full-stack architecture and deployment, user-integrity tracking, product optimization** |
| Ricardo Resnik Messing | Co-CEO, Business & Research: market research, competitive analysis, business model |

---

*2.5 billion people go to bed tonight. Most will scroll until midnight. Helix gives them a reason not to.*
