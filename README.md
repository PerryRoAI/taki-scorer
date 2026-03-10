# Taki Scorer (מיכאקי)

אפליקציית ניקוד טאקי יורד - טורניר פירמידה

A mobile-first web app for scoring the Taki card game. No installation or internet required — just open `index.html` in a browser.

## Features

- **2–10 players** with customizable names
- **Card counter** per player — tap to decrement on each card drop
- **Auto-finish** — last remaining player is automatically marked as last place
- **Undo** — reverse the last card drop from the settings panel
- **Move log** — timestamped log of every drop during the game
- **Tournament log** — tracks winners across multiple games in a session
- **Victory sounds** — applause plays when each player finishes
- **Sound controls** — toggle intro song and all sounds independently
- **Haptic feedback** — vibration on card drops (mobile devices)
- **Persistent state** — game state saved to localStorage; survives page refresh
- **RTL Hebrew UI** — designed for Hebrew-speaking players
- **Dark glassmorphism design** — looks great on any screen size

## Usage

1. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
2. Set the number of players and enter their names
3. Tap **התחל משחק ▶** to start
4. On each player's turn, tap their card counter to reduce it by 1
5. When a player drops their last card, they're marked as a finisher with their rank
6. After all players finish, start a new game or reset to defaults

## Settings Panel

Access via the ⚙️ gear icon during a game:

| Option | Description |
|--------|-------------|
| 🎵 Intro song | Toggle the opening music |
| 🔊 All sounds | Toggle all sound effects |
| ↩ Undo last drop | Revert the most recent card drop |

## Project Structure

```
taki-scorer/
├── index.html          # Main app (self-contained)
├── LOGO.png            # App logo
├── *.mp3               # Sound effect files
└── index_ver*.html     # Archived version snapshots
```

## Tech Stack

- Vanilla HTML, CSS, JavaScript — no frameworks, no build step
- Web Audio API for sound effects
- localStorage for persistence
- Vibration API for haptics

## Credits

Built by [PerryProAI](https://perryproai.com)
