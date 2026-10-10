# 🔞 NSFW Discord Bot - Modular Media & Entertainment Bot

A high-performance modular Discord bot with a wide variety of entertainment and media commands, organized into categorized handler modules.

---

## ✨ Features
- **Extensive Command Suite**: Over 20+ specialized media, utility, and entertainment commands.
- **Categorized Command Handler**: Clean command architecture allowing easy addition and customization of new modules.
- **Discord.js Architecture**: Built on Discord.js with modern slash command and prefix support.
- **Permission & Safety Controls**: Automatic Age-Restricted (NSFW) channel verification to ensure compliance with Discord terms.

---

## 📁 Repository Structure
```
NSFW-Discord-Bot/
├── commands/        # Categorized command modules
│   └── nsfw/        # Individual command handlers (4k, anal, ass, boobs, etc.)
├── .gitignore       # Git exclusion rules
├── LICENSE          # Open-source license
└── README.md        # Comprehensive documentation
```

---

## 🚀 Installation & Setup

### Prerequisites
- Node.js 16.x or higher installed.

### Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/loveslaw/NSFW-Discord-Bot.git
   cd NSFW-Discord-Bot
   ```

2. Install dependencies:
   ```bash
   npm install discord.js axios
   ```

3. Configure environment:
   Create a `.env` file or set environment variables:
   ```env
   DISCORD_TOKEN=YOUR_BOT_TOKEN
   PREFIX=!
   ```

4. Run the bot:
   ```bash
   node index.js
   ```

---

## ⚠️ Safety & Compliance
This bot enforces Discord's NSFW channel checks. Commands must only be executed within channels designated as Age-Restricted (18+) on Discord.
