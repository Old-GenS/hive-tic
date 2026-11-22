# Hive Five

A slow, sunny game of tic-tac-toe with bees, blossoms and gentle ambient music.

## Play

Open `index.html` in any modern browser — no build step, server or dependencies required.

- **vs Hive Mind** — play as the Bees against a mostly-optimal computer opponent.
- **2 Players** — pass the phone or keyboard back and forth.
- Tap/click a cell (or use Tab + Enter) to place your mark.
- Three in a row wins; scores and round starters alternate.
- The **Music** button in the top corner toggles the ambient soundtrack.

## GitHub Pages

Deployment is configured in `.github/workflows/pages.yml`. Every push to `main` publishes the game from `index.html`, and the workflow can also be started manually from the Actions tab.

If the site is not live after the first push, enable the publishing source once:

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Run **Deploy Hive Five to GitHub Pages** from the Actions tab (or push to `main` again).

The site will then be available at `https://<owner>.github.io/hive-test2/`.

## Notes

- Everything lives in one file: markup, styles, game logic, SVG artwork and audio.
- Music and sound effects are synthesized in real time with the Web Audio API, so there are no audio files or network requests.
- Mobile-first layout with safe-area support, large touch targets and reduced-motion support.
- Music begins on the first interaction, as browsers require a gesture before playing audio.
