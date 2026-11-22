# Hive Five

A slow, sunny game of tic-tac-toe with bees, blossoms and gentle ambient music.

## Play

Open `index.html` in any modern browser — no build step, server or dependencies required.

- **vs Hive Mind** — play as the Bees against a mostly-optimal computer opponent.
- **2 Players** — pass the phone or keyboard back and forth.
- Tap/click a cell (or use Tab + Enter) to place your mark.
- Three in a row wins; scores and round starters alternate.
- The **Music** button in the top corner toggles the ambient soundtrack.

## Notes

- Everything lives in one file: markup, styles, game logic, SVG artwork and audio.
- Music and sound effects are synthesized in real time with the Web Audio API, so there are no audio files or network requests.
- Mobile-first layout with safe-area support, large touch targets and reduced-motion support.
- Music begins on the first interaction, as browsers require a gesture before playing audio.
