# 👑 THE LAST CROWN

## RISE OF EMPIRES · OFFLINE 4X STRATEGY

**THE LAST CROWN — RISE OF EMPIRES** is a Persian, single-player, offline 4X strategy game. The player leads a realm, develops its economy, explores a hex-based world, expands territory, researches technologies, builds an army, fights rival dynasties, and manages diplomacy.

The game runs locally in a modern browser without an account, backend, or online game server.

## Core Gameplay Systems

- **Realm selection:** choose a starting dynasty with its own identity and bonuses.
- **Explore & expand:** reveal a hex-based world and claim connected territory.
- **Economy:** manage resources such as gold and food and maintain realm stability.
- **Construction:** queue buildings and develop settlements.
- **Research:** progress through the technology system.
- **Military:** recruit and manage forces, declare wars, and resolve battles.
- **Diplomacy:** interact with rival dynasties and manage relations.
- **Season-based progression:** construction, upkeep, and realm stability are tied to the game's turn and season flow.
- **Local persistence:** save game progress and preferences in browser storage.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Game shell and interface structure |
| CSS3 | Layout, visual identity, and animation |
| JavaScript | Game state, simulation, interaction, and rendering |
| DOM / Canvas APIs | World and interface presentation |
| LocalStorage | Local game data and preferences |
| Web Audio API | Audio playback and music controls |
| Embedded JPEG / MP3 data | Keeps artwork and soundtrack available offline |

## Project Structure

```text
THE-LAST-CROWN/
├── index.html
├── css/
│   └── main.css
├── js/
│   ├── audio-data.js
│   ├── assets.js
│   └── main.js
└── THE_LAST_CROWN_INFO.md
```

### File Responsibilities

- `index.html` — document metadata, application container, and stylesheet/script references.
- `css/main.css` — all original interface styles, including the additional visual-polish rules and embedded artwork.
- `js/audio-data.js` — embedded soundtrack data.
- `js/assets.js` — artwork constant and soundtrack data URI assembly.
- `js/main.js` — gameplay systems, state management, interactions, and rendering.

The gameplay code remains in one main JavaScript file because its systems share state and functions extensively. The source is separated by language and responsibility without arbitrarily splitting tightly coupled logic. The original artwork and soundtrack remain embedded, preserving the self-contained offline experience.

## Run Locally

1. Download or clone the repository.
2. Open `THE-LAST-CROWN/index.html` in a modern browser.
3. Keep the `css/` and `js/` directories beside the HTML file.

No package installation, build step, backend, or network connection is required for local operation. Browser policies may require a user interaction before audio playback begins. Save data is stored in the current browser and is not synchronized between devices.

## Language

The in-game interface is primarily Persian (Farsi) and uses a right-to-left layout.

## Developer

**Taha Hassarki** · [GitHub Profile](https://github.com/TahaDev24)

AI tools were used as development assistance. The project's direction, feature choices, and final decisions belong to the developer.

---

**ONE CROWN. MANY EMPIRES. ONE LEGACY.**
