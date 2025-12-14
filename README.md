# 🎵 Rhythm Master
### by **Sublime Sounds**

A blockchain-powered rhythm game built for the **WAX ecosystem**, featuring NFT-powered tracks, video/audio backgrounds, competitive leaderboards, and Season Pass access control.

> **Status:** 🧪 Beta Testing Phase  
> **Current Version:** `v0.9.0-beta`

---

## 🚀 Badges

![Version](https://img.shields.io/badge/version-0.9.0--beta-ec4899)
![Status](https://img.shields.io/badge/status-beta-testing-yellow)
![Platform](https://img.shields.io/badge/platform-WAX%20Blockchain-purple)
![Built With](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JavaScript-blue)
![License](https://img.shields.io/badge/license-proprietary-red)

---

## 🎮 About the Game

**Rhythm Master** is a fast-paced rhythm game where players tap falling notes in time with music NFTs they own on WAX.

Each track NFT can include:
- 🎵 **Audio**
- 🎬 **Video backgrounds**
- 🖼️ **Static artwork**

Gameplay reacts visually and physically with:
- Lane pulses
- Sparks
- Screen shake on **SUBLIME!** hits
- Score multipliers (x2 / x3)

---

## 🧩 Key Features

- 🔗 **WAX Cloud Wallet login**
- 🪙 **NFT-based track selection**
- 🎥 **Non-looping video backgrounds**
- ⏸️ **Orientation-aware pause/resume**
- 📱 **Mobile-first gesture handling**
- 🏆 **Local leaderboard (per track & season)**
- 🎟️ **Season Pass NFT gating**
- 🛡️ **Admin bypass support**
- ⚡ **Multiplier bars (x2 / x3)**
- 📊 **Accuracy-based scoring**

---

## 🔐 Access Control

### Season Pass Requirement
Players must own a specific **Season Pass NFT template** to start gameplay.

- Start button is disabled if no pass is detected
- Admin wallets bypass this restriction

```js
const SEASON_PASS_TEMPLATE_ID = "123456"; // set per season
const ADMINS = ["a1hd.wam", "fs1r2.wam"];
