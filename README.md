# ahasanpsu.github.io

Personal academic website of **Md. Ahasan Ahamed** — Ph.D. candidate in Electrical Engineering (Penn State); biosensing, diagnostics, nanopore sensing, and microfluidics. Live at https://ahasanpsu.github.io

## How it is built
Static site (plain HTML + one shared CSS file). No build step, no dependencies. GitHub Pages serves it directly from the `main` branch.

## Files
| File | Purpose |
|------|---------|
| `index.html` | About / home (intro, highlights, research interests, featured video) |
| `publications.html` | Full publication list (numbered, year-grouped) + conferences |
| `research.html` | Research projects, funding, translational work |
| `teaching.html` | Teaching experience + courses taught |
| `education.html` | Degrees, awards |
| `contact.html` | Contact details |
| `style.css` | **Shared stylesheet — edit here to change the look of every page** |
| `nav.js` | Mobile navigation toggle |
| `Md_Ahasan_Ahamed_CV.pdf` | CV download |

## Editing
- To change **content**, edit the relevant `.html` file (each page links `style.css` and `nav.js`).
- To change **styling/colors/fonts**, edit `style.css` once; it applies to all pages.
- Commit to `main` and GitHub Pages redeploys automatically within ~1 minute.

## Notes
- Publication thumbnails and two research figures are linked from the Guan Lab site assets.
- To host the ACS demo video inline, add the `.mp4` file to the repo and point the home-page video at it.
