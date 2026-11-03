# Othello Pro — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Classic Othello (Reversi) against a real minimax AI. Sandwich enemy discs to
flip them, fight for corners, and dominate the 8x8 board. Three difficulty
levels from casual greedy to 4-ply search.

(194 characters)

## Details

- Genre: Board game / Strategy / Casual
- Controls: Mouse / Touch — tap a highlighted square to place your disc.
  Keyboard: arrows move the cursor, Enter/Space places.
- Rules: Standard Reversi — you play black and move first; place a disc to
  sandwich one or more enemy lines in any of 8 directions and they all flip;
  no legal move = auto-pass; both players pass or the board fills = game
  over, most discs wins.
- AI: Easy (mostly random with a greedy streak), Normal (greedy on position
  weights + flip count), Hard (iterative-deepening minimax 2-4 ply with
  position weights + mobility, depth scales with empty squares, always under
  1 second per move).
- Features: Ripple 3D disc-flip animations, toggleable legal-move hints,
  last-move marker, live disc counts, pass banners, endgame board-share bar,
  per-difficulty win/loss/draw records saved locally, mute toggle.
- Tech: Vanilla JavaScript, Canvas, WebAudio (all sounds synthesized).
  Single-file HTML5, no external assets, works offline once loaded.
  No frameworks, no tracking, no external links.

## Tags
othello, reversi, board game, strategy, ai, minimax, classic, casual, abstract, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to any screen, portrait-friendly, mouse/touch/keyboard)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: TBD (1280x720)
- [ ] Screenshots: TBD

## itch.io
- Upload zip (othello-ai-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480x464 (responsive), kind: html
- Pricing: $0 (donations optional)
