# Rhythm Master – Developer Notes

---

## 🎮 Core Systems
- Notes are spawned on a time-based schedule
- Visual position uses dynamic hit-line alignment
- Scoring is time-based, not position-based

---

## ⏱ Hit Detection
- HIT_WINDOW = 180ms
- HIT_BUFFER = +30ms (mobile forgiveness)
- Final check: bd <= HIT_WINDOW + HIT_BUFFER

---

## 🔁 Restart Logic
- `allowFreeRestart` controls payment bypass
- `suppressScoreSubmit` prevents leaderboard writes
- Restarts reset visuals but not payment unless exhausted

---

## 📱 Fullscreen & Orientation
- Game enters fullscreen on Start
- Orientation locked to landscape when supported
- Hit line Y-position recalculated dynamically

---

## 💳 Payments
- SSN transfers handled via WAXJS or Anchor
- Admins bypass payment logic
- Payment required per track, not per session

---

## 🗄 Leaderboards
- Stored in Supabase
- Keyed by:
  - season
  - track name
  - user account
- Only higher scores overwrite existing records
