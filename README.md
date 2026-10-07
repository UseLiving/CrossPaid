# CrossPaid

Plan where each fee goes before you move any money.

A single-page planning sandbox (no build step) for splitting creator fees between wallets. HTML, CSS and JavaScript all live in `index.html`.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000

## What's in it
- A planner: up to five named routes, each with a share, a wallet address check and duplicate detection
- A route map with glowing pulses, plus per-route amounts for a sample number of fees
- Copy draft plan (only when shares total exactly 100% and addresses are valid)
- A checklist for before anything goes live, a short "how it works" and a questions section
- Connect Wallet (Phantom, Solflare, Backpack): reads the public address only, so it can be reused in a route. It cannot sign or send anything.
- Light and dark mode, and a reduced-motion fallback

## Notes
CrossPaid is a planner. It never signs or sends anything, has no token, and is not affiliated with any launch platform. It is not financial or tax advice. A real fee split has to be created in the platform's own official tool.

## Structure
- `index.html`: the whole site (loads Geist and Geist Mono from Google Fonts, with system fallbacks)
- `assets/`: icon, mark, profile pictures and X banner
