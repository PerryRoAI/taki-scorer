# Changelog

All notable changes to this project are documented here.

## [Unreleased]

## [2.1.0] — 2025

### Changed
- Victory applause sound now plays for **all** finishing positions, not just first place
- Improved last-player auto-finish reliability

### Added
- Undo sound effect when reverting a card drop
- Larger player name and button sizes for easier tap targets

## [2.0.0] — 2025

### Added
- **Tournament log** — persistent table tracking winners across games with timestamps
- **Pre-game setup screen** — dedicated screen to configure players before starting
- **New game flow** — start a fresh game with the same players without full reset
- **Vibration toggle** — enable/disable haptic feedback in settings
- **Victory sound** — audio cue when a player finishes

### Fixed
- Auto-end game edge case when the last player finishes

## [1.5.0] — 2025

### Added
- **Settings panel** — slide-up drawer accessible via gear icon during gameplay
- **Undo last drop** button in settings panel
- **Sound toggles** — separate controls for intro song and all sounds
- **About section** with PerryProAI link and version info

### Changed
- Increased about section font sizes and brightness

## [1.0.0] — 2025

### Added
- **UX improvements**: larger fonts, auto game-end when all players finish
- **Haptic feedback** on card drops (mobile)
- Long-press threshold tuning (1.5 s)
- Move log (drop log) with player, cards remaining, and timestamp

## [0.1.0] — 2025

### Added
- Initial release: basic Taki card scorer
- 2–10 player support with customizable names
- Card counter per player with tap-to-decrement
- Dark RTL Hebrew UI
- localStorage persistence
