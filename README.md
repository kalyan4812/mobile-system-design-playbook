# Mobile / Android System Design 

A self-contained study guide covering **40 system designs** (30 mobile/Android product
designs + 10 classic LLD/OOD warm-ups), sorted easy → hard, plus reusable
top-level material so you can answer *any* mobile system design prompt.

## What's new in v2

Each of the 40 systems now includes:

- **30-second elevator pitch** to memorize for your opening
- **ASCII architecture diagram** (visual recall during the interview)
- **Back-of-envelope numbers** (DAU, RPS, storage, bitrate)
- **Junior vs Staff signal** contrast (level calibration)
- **Don't-say-this** trap to avoid
- **Related systems** cross-links to traverse patterns
- **Expanded cross-questions** (8-10 per system, was 4-5)

Plus new top-level material:

- **Cheat sheet** — one-line hook for every system (read the night before)
- **Universal 90-second opening script** (the words to say in seconds 0-90)
- **Universal cross-questions** (asked of every design — process death, offline, auth, …)
- **Anti-patterns appendix** (the moves that drop you a level)
- **Glossary** — 50 must-know terms (Lamport clock to Widevine to Token Bucket)

Plus 5 new high-value systems:

- **#36 Live Streaming** (Twitch-mobile)
- **#37 A/B Testing & Feature Flag SDK**
- **#38 Crash Reporting SDK**
- **#39 E-commerce / Amazon Mobile**
- **#40 Wear OS / Phone Sync**

Plus interactive HTML features:

- 🌙 **Dark mode** toggle (auto-follows system, persisted)
- 🔍 **Search** (⌘K / Ctrl+K) — filters systems by any keyword
- 📌 **Sticky sidebar TOC** with active-section highlight
- ✓ **Mark as studied** per system (persisted in localStorage)
- 📋 **Copy code** button on every code block
- 🖨️ **Print-optimized** stylesheet (Cmd+P → Save as PDF)

## Files


| File                              | What it is                                    |
| --------------------------------- | --------------------------------------------- |
| `mobile-system-design-guide.html` | The full guide (409 KB). Open in any browser. |
| `mobile-system-design-guide.pdf`  | Print-ready PDF (~178 pages, 4.8 MB).         |


## Reading

- **Best experience**: open the HTML in a modern browser. You get dark mode,
search, sticky TOC, copy-code, mark-as-studied. Hit ⌘K / Ctrl+K to search.
- **Portable**: read the PDF on any device.
- **Cheat sheet only**: jump to "Cheat Sheet" in the TOC for the night-before pass.

## Re-generating the PDF

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless=new --disable-gpu --no-pdf-header-footer \
  --print-to-pdf=mobile-system-design-guide.pdf \
  "file://$(pwd)/mobile-system-design-guide.html"
```

## What's covered

### Easy — client-app fundamentals

1. Notes / TODO App with Sync
2. Weather App (API + caching)
3. Local Image Gallery
4. Calculator with History
5. News Reader (RSS-style feed)

### Medium — libraries & app-level systems

1. Image Loading Library (Glide / Picasso)
2. Generic Mobile Caching Library
3. Pagination Library (Paging 3-style)
4. Push Notification SDK (FCM-based)
5. Analytics SDK (offline-buffered)
6. Offline-First Sync Architecture
7. Twitter / Instagram Feed
8. Search with Autocomplete
9. Calendar App with Sync
10. File / Resumable Upload SDK

### Hard — large mobile products

1. WhatsApp-style Real-time Chat
2. Spotify (offline music streaming)
3. YouTube (video streaming + ABR)
4. Google Photos (upload + gallery)
5. Instagram Stories
6. Uber / Lyft Rider App
7. Google Maps + Turn-by-turn Nav
8. Netflix (downloads, DRM, ABR)
9. Tinder (swipe + matching)
10. Food Delivery (Swiggy / DoorDash)

### Classic LLD / OOD warm-ups

1. LRU Cache
2. Rate Limiter (Token Bucket)
3. Parking Lot
4. Elevator System
5. Chess Game
6. Snake & Ladder
7. Tic-Tac-Toe
8. ATM
9. Vending Machine
10. Splitwise

### Bonus — SDK & platform designs (v2)

1. Live Streaming (Twitch-mobile)
2. A/B Testing & Feature Flag SDK
3. Crash Reporting SDK
4. E-commerce / Amazon Mobile
5. Wear OS / Phone Sync

## How to study

1. **Two weeks out**: read the universal script + glossary; read 3 systems/day.
2. **One week out**: deep-dive your 5 weakest tiers; rehearse the elevator pitch out loud.
3. **Day before**: read the cheat sheet end-to-end; review anti-patterns.
4. **Day of**: skim the universal script + your weakest 2 systems.

Mark systems as studied in the HTML to track progress.
