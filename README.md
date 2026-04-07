# 🎤 LyricGuesser Discord Bot

A competitive music trivia bot built with `discord.py`. Challenge your server to guess songs based on lyric snippets, track high scores, and maintain winning streaks!

---

## ✨ Features
- **Lyric Trivia:** Pulls random song snippets from a local JSON database.
- **Dynamic Leaderboard:** Tracks scores per server to see who is the ultimate music fan.
- **Game Modes:** - `Normal`: Shows the artist name.
  - `Hard`: Hides the artist for a true challenge.
- **Streak System:** Earn bonus points for getting 3 songs right in a row!
- **Timed Hints:** Automatically sends a first-letter hint if the song isn't guessed quickly.

## 🛠️ Tech Stack
- **Language:** Python 3.10+
- **API:** [Discord.py](https://discordpy.readthedocs.io/)
- **Data:** JSON for snippet storage.
- **Environment:** `python-dotenv` for secure token management.

## 🚀 Setup & Installation

### 1. Prerequisites
- Python 3.10 or higher
- A Discord Bot Token (from the [Discord Developer Portal](https://discord.com/developers/applications))

### 2. Installation
Clone the repository and install dependencies:
```bash
git clone [https://github.com/YOUR_USERNAME/lyric-guesser-bot.git](https://github.com/YOUR_USERNAME/lyric-guesser-bot.git)
cd lyric-guesser-bot
pip install discord.py python-dotenv
