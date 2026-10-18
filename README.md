# ✂️ UnSubHub — The Dark Pattern & Subscription Destroyer

> **Bypass hidden menus, stop silent bank deductions, and demand instant refunds from subscriptions in 1-Click.**

[![License: MIT](https://img.shields.io/badge/License-MIT-rose.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg)](https://github.com)
[![Zero Cost](https://img.shields.io/badge/Hosting-100%25%20Free-blue.svg)](https://pages.github.com)

---

## 🎯 The Problem
Companies make **subscribing take 1 second**, but make **canceling a multi-page psychological maze** (known as *Dark Patterns* or *Roach Motels*).
- Hiding the cancel button deep inside sub-menus.
- Charging 50% early cancellation penalty fees (Adobe).
- Silently auto-debiting bank accounts via UPI autopay mandates even after uninstalling the app (Hotstar, Cult.fit, Truecaller).
- Refusing refunds claiming *"digital products are non-refundable"*.

## ⚡ The Solution: UnSubHub
**UnSubHub** is a 100% free, community-driven open-source directory and utility that gives consumers:
1. **Direct Hidden Cancellation URLs:** Jump straight to the real cancellation endpoint, skipping retention questionnaires and discount traps.
2. **Dark Pattern Warnings:** Explains the exact dirty trick the company uses (e.g. Adobe's 50% exit fee bypass trick).
3. **Legal Refund Demand Generator:** Pre-drafts a formal legal email citing the **Consumer Protection Act 2019** and **RBI Autopay Revocation Guidelines**, which forces support teams to process immediate refunds.
4. **UPI Mandate Kill Guides:** Step-by-step instructions to revoke auto-debit in PhonePe, Google Pay, and Paytm.

---

## 🚀 Live Demo
Open `index.html` in your browser, or host it on **GitHub Pages / Vercel** for free with zero configuration!

---

## 🛠️ How to Add a New Service
We welcome contributions! To add a service or company that is hard to cancel:
1. Fork this repository.
2. Edit `services.json` and add your entry:
```json
{
  "id": "brand-name",
  "name": "Brand Name",
  "category": "Streaming & OTT",
  "icon": "tv",
  "difficulty": "Hard",
  "darkPattern": "Explain the dirty trick here...",
  "directCancelUrl": "https://brand.com/direct/cancel/link",
  "instructions": [
    "Step 1...",
    "Step 2..."
  ],
  "refundEmail": "support@brand.com",
  "refundEligibleDays": 14,
  "legalClause": "Consumer Protection Act 2019"
}
```
3. Run `node convert.js` to update the offline fallback.
4. Submit a Pull Request (PR)!

---

## 💰 Monetization & Business Potential (For the Creator)
- **ProductHunt Launch:** Consumer rights tools frequently trend #1 on ProductHunt, bringing tens of thousands of users.
- **Sponsorships & Affiliates:** Recommend privacy-first virtual cards and secure financial tools.
- **Chrome Extension:** Package this tool as a free browser extension that automatically pops up whenever a user visits an active subscription page.

---

## ⚖️ License
Distributed under the **MIT License**. Free for personal and commercial use.
