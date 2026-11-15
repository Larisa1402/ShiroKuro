# ShiroKuro

Club page and live races for the ShiroKuro chess club on Chess.com.

- `index.html` – club page (includes the Races section)
- `races.html` – points and rating race widget, embedded in the club page
- `daily-points-race.json`, `weekly-rating-race.json` – written by GitHub Actions
- `top-wins-yesterday.json` – placeholder (no script writes it yet)
- `scripts/` – updater scripts; `.github/workflows/` – schedules; `data/` – weekly baseline state; `images/` – your images

Setup: enable GitHub Pages (main, root), give Actions read and write permission, run both workflows once, then replace `YOUR-USERNAME` and `YOUR-REPO` in the Races iframe in `index.html` with your Pages address.
