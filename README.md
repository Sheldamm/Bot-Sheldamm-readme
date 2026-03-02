<div align="center">

# 🤖 Bot Sheldamm
### Feature-rich WhatsApp Bot for Group Management

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green?style=flat-square&logo=node.js)](https://nodejs.org)
[![Version](https://img.shields.io/badge/Version-2.0.0-blue?style=flat-square)](https://github.com/Sheldamm)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()
[![License](https://img.shields.io/badge/License-Private-red?style=flat-square)]()

> ⚠️ **This is a showcase repository. Source code is private (commercial project).**  
> For rental inquiries, contact via the links below.

</div>

---

## ✨ Features

### 🤖 AI Chat
- Powered by **Groq AI** & **Google Gemini**
- Auto-reply with intelligent responses
- Fallback assistant for unanswered messages
- Context-aware conversations

### 🏷️ Auction System (Lelang)
- Full real-time auction management inside WhatsApp groups
- Auto-bidding detector
- Auction queue system (antri)
- Timer recovery — auctions resume after bot restart
- Payment tracking
- Admin controls

### ⏰ Alarm Scheduler
- Set daily or interval-based alarms
- Timezone support per group
- Persistent alarms (survive bot restarts)
- Group-specific alarm management

### 💼 Sewa (Subscription) Management
- Per-group subscription system
- Owner-controlled activation
- Multiple duration options
- Auto-expiry enforcement

### 🛡️ Group Protection
- Anti-link filter
- Anti-status view (anti-SW)
- DM protection
- Admin-only mode
- Permission checker

### 🎨 Utilities
- Sticker maker
- Image collage (Kolase)
- Image upscaler
- RFP (Request for Price) handler
- Typing indicator simulation
- Cooldown system

---

## 🛠️ Tech Stack

| Tech | Usage |
|------|-------|
| **Node.js 18+** | Runtime |
| **Baileys** | WhatsApp Web API |
| **LokiJS** | Persistent local database |
| **Groq SDK** | AI Chat (LLaMA) |
| **Google Generative AI** | Gemini AI integration |
| **PM2** | Process management & auto-restart |
| **Sharp** | Image processing |
| **FFmpeg** | Media conversion |

---

## 🏗️ Architecture

```
Bot-Sheldamm/
├── plugins/          # Command handlers (modular)
│   ├── lelang/       # Auction system
│   ├── sticker/      # Sticker maker
│   └── kolase/       # Image collage
├── services/         # Business logic & database
│   └── lelang/       # Auction engine
├── middlewares/      # Request pipeline (14 layers)
├── helpers/          # Utilities & schedulers
├── validators/       # Input validation
└── utils/            # Shared utilities
```

### Middleware Pipeline
```
Message In
  → Self Filter
  → Stale Message Filter
  → DM Protection
  → Sewa Check
  → Anti-Link Check
  → Anti-SW Check
  → Command Detector
  → AI Auto Reply
  → Admin Guard
  → Permission Checker
  → Command Executor
  → Fallback Assistant
  → Auto Bid Detector
  → RFP Handler
```

---

## 📊 Stats

- 🏠 **30+ Groups** actively using this bot
- ⚙️ **14 Middleware layers** for robust message handling
- 🔄 **PM2** managed — 24/7 uptime with auto-restart
- 💾 **LokiJS** — persistent data across restarts

---

## 📬 Contact & Rental

> 💡 This bot is available for **rental (sewa)** for WhatsApp groups.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Sheldamm-black?style=for-the-badge&logo=github)](https://github.com/Sheldamm)
[![Instagram](https://img.shields.io/badge/Instagram-mfariki10__-E1306C?style=for-the-badge&logo=instagram)](https://instagram.com/mfariki10_)
[![Website](https://img.shields.io/badge/Website-Portfolio-00ff88?style=for-the-badge&logo=firefox)](http://157.10.161.155)

</div>

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/Sheldamm">Sheldamm</a> © 2026</sub>
</div>
