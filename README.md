# Bandits Scouting

Opponent scouting reports for the Bandits — hitter approach cards, lineup
breakdowns, and pitching staff reads built from GameChanger exports.

**Live site:** https://<your-username>.github.io/bandits-scouting/

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page with a grid of all scouting reports |
| `scout-template.html` | Blank template — copy this for each new opponent |
| `scout-sample.html` | Filled-in demo showing the template in use |
| `style.css` | Shared burnt-orange / charcoal theme |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Adding a new scouting report

1. Copy `scout-template.html` to `scout-<opponent-name>.html`.
2. Replace every `{{PLACEHOLDER}}` with real data.
3. Duplicate batter / pitcher / lineup-row blocks as needed; delete extras.
4. Add a tile to the grid in `index.html` pointing at the new file.
5. Commit and push — Pages redeploys automatically.

## Enabling GitHub Pages

In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root → Save.**
The site goes live at the URL above within a minute or two.

## Theme

Colors live as CSS variables at the top of `style.css` (`--orange`,
`--bg`, etc.) — change them once there to restyle every page.
