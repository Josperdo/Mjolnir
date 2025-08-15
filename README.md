# Mjolnir (In Progress)
**The Ban Hammer with a Stopwatch**

Mjolnir is a Discord bot that tracks playtime for a target game (default: *League of Legends*) and enforces configurable rules with style — milestone announcements, opt-in consent, and an admin-controlled ON/OFF switch.

---

## Features
- **Playtime Tracking** – Records how long opted-in members play the target game.
- **Milestone Announcements** – Custom/randomized messages when lifetime playtime hits thresholds (e.g., 10h, 25h, 50h).
- **Consent-Based** – Users must `/opt-in` before tracking starts.
- **Admin Controls** – `/hammer on|off|status` to enable/disable tracking globally.
- **SQLite Persistence** – Stores sessions, milestones, and settings locally.
- **Configurable** – Change thresholds, target game, and announcement channel in `.env`.

---

## Quick Start

### 1) Clone & Install
```bash
git clone https://github.com/Josperdo/Mjolnir.git
cd Mjolnir
python -m venv .venv && source .venv/bin/activate
pip install -U pip
pip install -e ".[dev]"

