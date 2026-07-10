# Changelog

All notable changes to the **Arcade Dashboard** project will be documented in this file.

## [Unreleased] - 2026-07-09

### Added
- Firebase Realtime Database integration for live lobby player counts
- "Last Updated" timestamps on lobby badges
- Smooth fade transitions when updating player counts
- Better error handling and fallback to simulation mode if Firebase fails to initialize
- Console logging for Firebase connection status

### Improved
- More natural and stable lobby player count simulation (as fallback)
- Code organization and maintainability
- Visual polish on lobby badges and timestamps

### Changed
- Updated lobby update logic to work with real Firebase data or simulation
- Restructured Firebase initialization to be more robust

## [2026-07-09] - Initial Enhanced Version

### Added
- Full achievement system with localStorage persistence
- Search functionality across games and tools
- Simulated live lobby updates with smooth animations
- Responsive grid layout
- Hover effects and pulse animation on lobby badges
- Demo interactions (clicking cards unlocks achievements)

### Features
- Featured Games section
- Game Tools & Apps section
- Local Achievements sidebar
- Mobile-friendly responsive design

---

**Project**: Arcade Dashboard (HTML + CSS + JS + Firebase)
**Hosting**: GitHub Pages / html.onlineviewer
**Backend**: Firebase Realtime Database (for live player counts)

