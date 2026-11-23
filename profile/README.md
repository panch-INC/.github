<div align="center">

# ⚡ panch INC.

**High-performance, user-first communication platform and open app ecosystem.**

[🌐 Open Web App](https://panchline.ru/messenger) •
[🖥️ Download Desktop](https://panchline.ru/download) •
[📱 Download Android APK](https://panchline.ru/download/android) •
[⚙️ Self-Hosted Server](https://github.com/panch-INC/panchline)

</div>

---

### 🌟 PanchLine Ecosystem Repositories

| Component | Repository | Technology | Description |
| :--- | :--- | :--- | :--- |
| ⚙️ **Core Server** | [**`panchline`**](https://github.com/panch-INC/panchline) | Go 1.24, Postgres 18, Redis 8, LiveKit SFU | Unified modular daemon (`panchlined`), voice signaling, outbox worker, and Bot API |
| 🌐 **Web Client** | [**`panchline-web`**](https://github.com/panch-INC/panchline-web) | React 19, TypeScript, Vite, WebRTC | Official responsive web application and installable PWA |
| 🖥️ **Desktop Client** | [**`panchline-desktop`**](https://github.com/panch-INC/panchline-desktop) | Electron, Vite, TypeScript | Native desktop app with tray, screen sharing with audio loopback, and auto-updates |
| 📱 **Android Client** | [**`panchline-android`**](https://github.com/panch-INC/panchline-android) | Kotlin, Jetpack Compose, Media3 | Native mobile app with LiveKit WebRTC, FCM push notifications, and gestures |

---

### 🚀 Key Features

* **Realtime Messaging**: 0-RTT delivery, Markdown formatting, instant search, message editing, reactions, voice messages, and video notes (кружочки).
* **Voice Spaces & Channels**: Discord-style servers with low-latency voice rooms powered by LiveKit SFU and crystal-clear audio.
* **Media & Social Streams**: Live video streaming (MediaMTX RTMP/HLS), shorts/reels player, and personal profile walls.
* **Extensible Bots & Mini-Apps**: Telegram-compatible Bot API, inline search results, interactive canvas apps, and JavaScript SDK.
* **Self-Hostable**: Simple single-command deployment via Docker Compose.

---

### 🛠️ Quick Start (Self-Hosted)

```bash
# Clone the server repository
git clone https://github.com/panch-INC/panchline.git
cd panchline

# Configure your environment
cp .env.example .env

# Start all platform services
bash start.sh
```

---

<div align="center">
  <sub>Built with ❤️ by panch INC. · <a href="https://panchline.ru">panchline.ru</a></sub>
</div>
