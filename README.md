# Lagator Group website

Website of the Lagator Group, University of Manchester. Plain HTML and one
stylesheet, with no build step: open `index.html` in a browser to preview it.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `research.html` | Research |
| `publications.html` | Publications |
| `team.html` | Team |
| `opportunities.html` | Opportunities |

All styling is in `styles.css`. Images are in `photos/`, and research figures
in `photos/research/`. `gantt.jpeg` is the group history chart on the Team page.

## Common edits

- **Add a paper:** in `publications.html`, copy an `<article class="paper">`
  block, edit the journal, title, link and authors. Wrap lab members in `<b>`.
  Newest papers go first.
- **Add a team member:** in `team.html`, copy an `<article class="person">`
  block. Save their photo as `photos/<name>.jpg`. If there is no photo, a tile
  with their initials is shown.
- **Change text:** edit it directly in the relevant `.html` file.

## Publishing

The site is served by GitHub Pages from the `main` branch. Changes pushed to
`main` go live within a few minutes.
