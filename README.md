# 🤖 Allowed-bot - WiFi Portal Authorization System

Telegram Bot ကို အသုံးပြု၍ WiFi Captive Portal ကို စီမံခန့်ခွဲနိုင်သော စနစ်။

## ✨ Features

- 🔐 Admin-only commands with authentication
- 📝 Add/Remove authorized users
- 📋 List all authorized users
- ⏳ View pending users
- 🚫 Blacklist system for unauthorized users
- ⏱️ Session timeout and auto-cleanup
- 🛡️ Rate limiting for security
- 💾 Persistent storage of user data
- 🌐 Automatic portal URL generation

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/zarni1mobile12200/Allowed-bot.git
cd Allowed-bot

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env
# Edit .env with your credentials

# Run the bot
python main.py
