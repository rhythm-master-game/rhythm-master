# Changelog
All notable changes to **Rhythm Master** will be documented in this file.

This project follows **Semantic Versioning**:  
`MAJOR.MINOR.PATCH`  
and is currently in **Beta**.

---

## [0.9.0] – Beta Release Candidate  
**Status:** Feature-complete beta  
**Date:** 2025-09-XX

### Added
- Mobile orientation detection with **pause-on-rotate**
- Full-screen rotate-device overlay during gameplay
- Automatic resume when returning to landscape
- Non-looping video NFT backgrounds (game ends with video)
- START_DELAY before notes spawn
- Multiplier pickup notes (x2 / x3)
- Screen flash effect on multiplier activation
- Restart button on Game Over screen
- Local leaderboard persistence per track & season
- Admin wallet bypass for Season Pass requirement
- Ad slot layout (6 slots + branded placements)
- Dynamic NFT track loading (audio / video / image priority)

### Changed
- Improved mobile touch handling (pointer events only during play)
- Refactored scroll-lock logic to avoid page freeze on mobile
- Gameplay loop now safely pauses during orientation changes
- Start button gated behind Season Pass NFT ownership
- Video NFTs take priority over static images when both exist
- Audio/video playback synced to gameplay loop

### Fixed
- iOS Safari scrolling freeze during gameplay start
- Lost lane hit effects (pulse, sparks, shake)
- Muted background video playback
- Notes persisting after game end
- WAX login failures caused by reinitialisation
- Restart logic resetting multipliers and timers correctly

---

## [0.8.0] – Mobile Stability & UX Update  
**Date:** 2025-08-XX

### Added
- Mobile-only rotate-for-best-experience hint
- Tablet viewport scaling safeguards
- Visual hit judgements (SUBLIME / OK / MISS)
- Lane pulse animations and camera shake
- Background image support per NFT track

### Changed
- Improved viewport meta configuration
- Refined touch-action rules for lanes vs page
- Reduced accidental gesture blocking on mobile

### Fixed
- Lane interaction not registering on some Android devices
- Judge text not appearing on perfect hits
- Game loop desync on slower devices

---

## [0.7.0] – NFT & WAX Integration  
**Date:** 2025-07-XX

### Added
- WAX Cloud Wallet login
- NFT ownership detection via AtomicAssets API
- Track selection from owned NFTs
- Season Pass NFT gating (template-based)
- Admin wallet override
- Local leaderboard storage

### Changed
- Start button disabled until wallet login
- Track selector locked until NFTs are loaded

### Fixed
- WAX login state resetting on UI changes
- Track selector breaking login flow

---

## [0.6.0] – Core Gameplay  
**Date:** 2025-06-XX

### Added
- Rhythm gameplay engine
- Falling note system
- Accuracy-based scoring
- Combo tracking
- Multiplier HUD
- Game Over overlay

### Changed
- Timing window tuned for mobile input latency

---

## [0.5.0] – Visual Foundation  
**Date:** 2025-05-XX

### Added
- Lane system (5 lanes)
- Hit line
- Background container
- Spark hit effects
- Sublime Sounds branding

---

## [0.4.0] – Initial Prototype  
**Date:** 2025-04-XX

### Added
- Basic UI layout
- Static lanes
- Placeholder scoring
- Early concept visuals

---

## Planned
- Cloud-backed leaderboards
- Player profiles & progression
- Achievements & mintable rewards
- Multiplayer modes
- PWA support
- Anti-cheat & analytics
- Seasonal events

---

**Maintained by:** Sublime Sounds  
**Project:** Rhythm Master  
**Status:** Beta (Pre-Launch)
