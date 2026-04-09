# 🎤 LyricGuesser Discord Bot

A competitive music trivia bot built with **discord.py**. Challenge your server to guess songs based on lyric snippets, track high scores, and maintain winning streaks!

---

## ✨ Features

* **Lyric Trivia:** Dynamically pulls random song snippets from your local `snippets.json` database.
* **Dynamic Leaderboard:** Tracks scores per server so you can see who the ultimate music fan is.
* **Game Modes:**
    * **Normal:** Includes the artist name in the prompt.
    * **Hard:** Hides the artist for a true challenge.
* **Streak System:** Earn a **+2 bonus** for getting 3 songs right in a row!
* **Timed Hints & Locking:**
    * **10 Seconds:** Bot drops a first-letter hint automatically.
    * **20 Seconds:** The round "locks"—you can still guess, but no points are awarded and streaks are reset.

---

## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **API:** Discord.py
* **Data:** JSON (`snippets.json`) for snippet storage.
* **Environment:** `python-dotenv` for secure token management.

---

## 🚀 Setup & Installation

### 1. Prerequisites
* **Python 3.10 or higher** installed.
* **A Discord Bot Token:** Obtain this from the [Discord Developer Portal](https://discord.com/developers/applications).
    * *Note: Under the "Bot" tab, you **must** enable the "Message Content Intent" toggle.*

### 2. Install Dependencies
Run this command in your terminal:
```bash
pip install discord.py python-dotenv
```

### 3. Project Setup
* **In your project's root folder, create a new file named `.env` and put your DISCORD token in this format `DISCORD_TOKEN=your_token_here`
* *Next, insert the JSON file into the same folder. *

### 4. Run the Bot and enjoy!

