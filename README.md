# Know Your Agent

A 3-minute browser game: an AI agent pays a coffee company's invoices, and you decide what it may pay.

## Publish on GitHub Pages (about 5 minutes)

1. **Create the repo.** On github.com, create a new public repository named `know-your-agent`. Upload `index.html` and `preview.png` (Add file > Upload files > Commit).
2. **Turn on Pages.** Settings > Pages > Build and deployment > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` > Save. After a minute the game is live at `https://YOUR-GITHUB-USERNAME.github.io/know-your-agent/`.
   Then edit `index.html` and replace `YOUR-GITHUB-USERNAME` (2 places, near the top) with your GitHub username, so LinkedIn shows the preview image.
3. **Turn on visitor counting (free).** Sign up at goatcounter.com, choose a code (for example `knowyouragent`). In `index.html`, replace `YOUR-CODE` with that code and commit.
   Your dashboard is then at `https://YOUR-CODE.goatcounter.com`.

## What you will see in GoatCounter

- **Visitors and page views** for the game, by day, with referrers (LinkedIn), countries, browsers and screen sizes.
- **Game events** (shown as separate rows, under "event/..."):
  - `start-game` · players who pressed Start
  - `level-1-complete`, `level-2-complete`
  - `scale-it-0-stars` … `scale-it-3-stars` · how players did on the rules level
  - `game-finished` · reached the results screen
  - `out-of-lives` · lost all three lives
  - `share-score` · copied their score to share

GoatCounter uses no cookies and collects no personal data, so the game needs no cookie banner.

## Check the LinkedIn preview

Paste your game URL into https://www.linkedin.com/post-inspector/ to see (and refresh) the preview card before posting.
