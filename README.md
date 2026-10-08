# ProjectShift

A crypto chart playground with a monitor that has feelings.

A single-page site (no build step): HTML, CSS and JavaScript all live in `index.html`.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000

## What's in it
- **The Shift Tape:** a simulated crypto chart (candles, line, area, MA 20, volume) that shifts between calm, pump, dump and rug. Includes a mood meter, a "make a call" game and a paper wallet with pretend money.
- **The monitor:** eyes follow your cursor, he gets nervous when you come close, angrier the more you poke him, and at maximum rage he explodes, rebuilds as a robot, punches the headline letters and splits the screen.
- **Shift Arena:** a blob-eating game under the monitor with bots. Live multiplayer needs the Claude-hosted page, which provides the shared room. Elsewhere it runs solo against bots.
- **Doodle pen, sticker book (16 stickers) and a ticker tape** driven by the chart. Progress is saved in the browser.
- Dark mode, reduced-motion support and a phone layout.

## Notes
Everything is a simulation. Prices are random numbers generated in your browser, nothing is a trade, there is no token, and it is not financial advice. The page loads Geist, Geist Mono and Caveat from Google Fonts and falls back to system fonts if they cannot load.

## Structure
- `index.html`: the whole site
- `assets/`: icon, profile pictures and the monitor character
