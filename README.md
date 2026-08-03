# atrahasis.github.io

Personal site for **Godfree Gale** (Atrahasis) — independent inventor working across advanced design, cross-disciplinary development, and industrial strategy.

- Site: [atrahasis.info](https://atrahasis.info)
- GitHub: [KingOfTheNight101](https://github.com/KingOfTheNight101)
- Featured work: Geometric Photonic RAM (G-PRAM) white paper in `White_Papers/`

## Stack

Static HTML, CSS, and JavaScript (no backend). Content is driven by `config/config.js`.

## Edit the site

1. Update `config/config.js` (profile, about, projects, links, images).
2. Open `index.html` locally, or push to GitHub Pages.

### Useful config fields

| Field | Purpose |
|-------|---------|
| `name`, `sex`, `age`, `phone`, `email`, `address` | Basic info (email is plain text for `mailto:`) |
| `welcome`, `about`, `motto` | Hero and about copy |
| `portfolio` | Project cards `[image, link, title, blurb]` |
| `skills`, `work`, `others` | Optional sections (hidden when empty) |
| `icon` | Contact icons `[svg, url, label]` |
| `url` | Background / avatar image paths |

## Structure

- `index.html` — page shell
- `config/config.js` — personal data
- `CSS/` / `JS/` — styles and scripts
- `images/` / `svg/` — assets
- `White_Papers/` — publications

## License

MIT (see `LICENSE`). Third-party libraries keep their original licenses (`THIRD_PARTY_NOTICES.md`).

Based on a lightweight static resume/portfolio template, customized for this site.
