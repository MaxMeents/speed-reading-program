# VELOCITY — Speed Reading Laboratory

A single-file, self-contained web app for speed reading training. Built with evidence-backed techniques and a futuristic electric-blue aesthetic.

**Live demo:** _enable GitHub Pages to get your link — see instructions below._

---

## Features

### Reading engines
- **RSVP Reader** — Rapid Serial Visual Presentation with optional ORP (Optimal Recognition Point) red-letter focal character, configurable 1–5 word chunking, punctuation-aware pause multipliers, bionic-bold option, and a 100–1000 WPM range.
- **Pacer Reader** — Narrow-column reading with a moving guide bar and optional metronome click to enforce saccade rhythm.

### Evidence-backed training drills
- **Schulte Table** — 3×3, 5×5, 7×7 grids for peripheral vision expansion. Features a center-fixation dot and miss tracking.
- **Tachistoscope** — Flash training for visual span. Numbers (1–9 digits), single words, and phrases at 50–800 ms.
- **Odd Word Out** — Semantic outlier detection under time pressure.
- **N-Back** — Working-memory training at levels 1 through 4.
- **Stroop Test** — Color/ink interference to train selective attention.
- **Find the Intruder** — Rapid peripheral scanning for a unique glyph in a sea of near-identical ones.

### System
- Seven built-in passages with comprehension quizzes (Gatsby, Einstein, JFK, Sherlock Holmes, Tao Te Ching, Darwin, Brian Greene) plus a custom-text paste-in.
- Progress dashboard with WPM trend chart.
- Full settings panel with JSON export/import.
- All data persisted locally in `localStorage` — nothing uploaded.

### Design
- Electric blue `#0A84FF` + cyan `#00D9FF` accent palette over pure white or pure black.
- Aurora gradients, fine grid mesh, glassmorphism cards.
- JetBrains Mono for numerics, Space Grotesk for UI, Literata for body text.
- Dark mode default; one-click theme toggle in the sidebar.

## Keyboard shortcuts
- `Space` — Play/pause RSVP; trigger flash in Tachistoscope.
- `←` `→` — Jump backward / forward 5 words in RSVP.
- `M` — Register a match in N-Back.

## Science
Peer-reviewed research (Keith Rayner et al., 2016) places the natural reading ceiling near **300 WPM** with full comprehension. Training to **350–450 WPM** is the realistic golden zone — a 40–80% gain — where speed and comprehension both climb. The drills here target the three evidence-backed levers: peripheral span, fixation reduction, and working memory.

## Running locally
Just open `index.html` in any modern browser. There is no build step, no bundler, no server required.

## License
MIT
