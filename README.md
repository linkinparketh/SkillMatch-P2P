# SkillMatch P2P

> **A decentralized peer-to-peer skill marketplace built on Intercom (TRAC Network)**

[![Fork of Intercom](https://img.shields.io/badge/fork-Intercom-brightgreen)](https://github.com/Trac-Systems/intercom)
[![Powered by TRAC](https://img.shields.io/badge/powered%20by-TRAC%20Network-yellow)](https://github.com/Trac-Systems)

---
<img width="1256" height="822" alt="image" src="https://github.com/user-attachments/assets/5d1b744f-2255-4791-80e7-c81c3f22b0eb" />

## 💡 What is SkillMatch P2P?

SkillMatch P2P is a **decentralized skill marketplace** where people can:

- 📢 **Post skills they offer** — dev, design, writing, marketing, and more
- 🔍 **Post skills they're seeking** — find the right collaborator for any project
- 🤝 **Connect directly P2P** — no middleman, no platform fees, no KYC
- 📡 **Broadcast listings over Intercom sidechannels** — real-time P2P negotiation
- 🔒 **Settle agreements peer-to-peer** — using TRAC/TNK or any agreed medium

Think of it as a **decentralized Fiverr / Upwork**, but fully P2P — negotiations happen over Intercom sidechannels and there's no central authority taking a cut.

---

## 🚀 Features

- **Live listings board** — skill offers and skill requests in one feed
- **Category filtering** — Dev, Design, Writing, Marketing, Other
- **Post a listing** — name, description, tags, rate, and your contact/Trac address
- **P2P contact modal** — copy a peer's Trac address to connect directly via Intercom
- **Live activity feed** — see real-time network activity
- **Fully client-side** — single HTML file, no backend needed

---

## 🖼️ App Screenshot

> See `screenshots/` folder for proof-of-work images.

---

## 🛠️ How to Run

Just open `index.html` in your browser. No installation needed.

```bash
git clone https://github.com/YOUR_USERNAME/intercom
cd intercom
open index.html
```

---

## 🏗️ How It Extends Intercom

This app uses Intercom's P2P sidechannel concept to:

1. **Broadcast skill listings** over the decentralized network
2. **Negotiate rates & terms** directly between peers without a central server
3. **Exchange contact/Trac addresses** for direct P2P settlement

The `index.html` is the frontend UI. In a full integration, the listing broadcast and peer discovery would use Intercom's socket-based sidechannel layer.

---

##  TRAC Reward Address

```
trac183pv7zxk705m29w6y2l9fvwntacps4vr6v0cua06qq507g22kxeqczfzks
```

>  **Replace `trac183pv7zxk705m29w6y2l9fvwntacps4vr6v0cua06qq507g22kxeqczfzks` with your actual Trac address to receive the 500 TNK payout.**

---

## 📁 Project Structure

```
/
├── index.html       # Main app — P2P skill marketplace UI
├── SKILL.md         # Agent skill instructions
├── README.md        # This file
└── screenshots/     # Proof of app working
```

---

## 🤖 Agent Integration

See [`SKILL.md`](./SKILL.md) for instructions on how AI agents can interact with SkillMatch P2P via Intercom.

---

## 📜 License

MIT — Fork freely, build freely.

---

*Built with ❤️ on the TRAC Network / Intercom stack*
