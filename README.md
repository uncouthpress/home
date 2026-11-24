# UNCOUTH

Static site for UNCOUTH, published by Uncouth Press. Plain HTML / CSS, no
build step. Works from `file://` by double-clicking `index.html`.

## Status

Pre-launch landing page with Lorem Ipsum placeholder content.
No real issues published yet. All links are `href="#"` placeholders.

## Files

| File              | What it is                                          |
|-------------------|-----------------------------------------------------|
| `index.html`      | Landing page.                                       |
| `css/landing.css` | Landing-page styles. Per-issue styles will live in each issue's own `vol1-noN/css/style.css`. |
| `images/`         | Landing images (empty for now — cover art placeholders). |
| `.nojekyll`       | Tells GitHub Pages not to run Jekyll.               |

## Local sanity check

```bash
# From this folder:
xdg-open index.html     # Linux
open index.html         # macOS
```

Or `python3 -m http.server 8000` and visit `http://localhost:8000/` if the
`file://` origin trips any browser-strict CSS/JS.

## Design and editorial references

See the project-level docs one level up (`../`):

- `../README.md` — brand overview and current status
- `../working/issues/home/design.md` — landing page design proposal (visual mockups)
- `../working/format-prompts/landing-page.md` — build/style guide for this page
- `../working/format-prompts/section-markers.md` — Tier 2 legal postures for sections
- `../working/docs/legal-position.md` — three-tier disclaimer system
- `../working/personas/house-counsel.md` and `opposing-counsel.md` — pre-publish review gates

## Next steps

Once first issue is ready:
1. Replace cover placeholder in hero with real cover image
2. Update "This Issue" featured piece with real title + standfirst
3. Fill in Lorem Ipsum issue cards with real titles, dates, dek lines
4. Add first issue's own folder (`vol1-no1/`) at this level
5. Replace all `href="#"` placeholders with real destinations
6. Claim and wire real social handles (@uncouthpress)
7. Wire up a real Beehiiv embed (currently a placeholder box)
