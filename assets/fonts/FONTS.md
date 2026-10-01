# Typefaces — provenance (self-hosted, OFL-1.1, no CDN)

These are the **drawn** faces the Department serves: **Cardo** (display), **Newsreader** (body),
**IBM Plex Mono** (mono) — the operator drew Direction A (design-language §3c, §6.1). The six other
candidates from the type draw, and the specimen that set all nine side by side, left the served tree
S01.0013 (operator ruling, NOTE-12.0215-2) and live in `projects/department-fwwc-website/specimen/`.
All are OFL-1.1, fetched from Google Fonts and **self-hosted** (design-language §3e/§3f: no
third-party font CDN on any served page). Latin subset only.

| Family | Role (§3c) | Designer / foundry | License |
|---|---|---|---|
| Cardo | Display — Didone / engraved-plate (Dir. A) | David J. Perry | OFL-1.1 |
| Newsreader | Body — reading serif (leader) | Production Type | OFL-1.1 |
| IBM Plex Mono | Mono — industrial-warm (leader) | Mike Abbink · Bold Monday · IBM | OFL-1.1 |

Source: Google Fonts (fonts.googleapis.com CSS2 API → fonts.gstatic.com woff2), fetched
at build time; the served page references only these local files. The OFL copyright +
license strings travel inside each `.woff2` name table; OFL-1.1.txt (this directory)
carries the license per the OFL bundling requirement.

Machine manifest: `_fonts-manifest.json` (slug · family · role · variant · file · bytes).
