# sungjay-kim.github.io

Personal academic site for **Sungjay Kim**, Ph.D. candidate in Biosystems Engineering at Seoul National University (SNUPHEL Lab).

Live at: <https://sungjay-kim.github.io>

## Stack

- Single-page static HTML/CSS, no JS framework and no build step.
- Typography: Inter (Google Fonts).
- Design system: NVIDIA design language (see [`DESIGN.md`](DESIGN.md), generated via [getdesign](https://www.npmjs.com/package/getdesign)).
- Two-surface architecture: black hero/footer + white body sections, single green accent `#76b900`.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire page (HTML + inline CSS) |
| `DESIGN.md` | NVIDIA design tokens used as the visual reference |
| `README.md` | This file |
| `.gitignore` | Ignored paths |

## Local preview

No build step. Open `index.html` directly in a browser, or serve locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

GitHub Pages serves `index.html` from the `main` branch automatically. To publish changes:

```bash
git add index.html
git commit -m "Update content"
git push
```

The live site refreshes in about 30 seconds.

## Sections

- **About**: bio, education, research interests, tools, experience, patent
- **Publications**: 2 first-author peer-reviewed papers, 6 co-author papers (collapsible), 3 manuscripts in preparation
- **Projects**: 5 funded research projects (IPET, RDA) plus the GWFSS challenge
- **Talks**: 4 oral presentations
- **Awards**: 6 scholarships and competition honors

## Contact

- Email: <sj0408@snu.ac.kr>
- Google Scholar: <https://scholar.google.com/citations?user=8Ty8q9sAAAAJ>
- LinkedIn: <https://www.linkedin.com/in/sungjay-kim/>
