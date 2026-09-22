# Candidate typefaces — provenance (self-hosted, OFL-1.1, no CDN)

These are the **candidate** faces for the Department type draw (design-language §3c).
Nothing here is chosen — the specimen (`../../type-specimen.html`) sets them all on
real content at both light levels so the operator can draw (§6.1). All are OFL-1.1,
fetched from Google Fonts and **self-hosted** (design-language §3e/§3f: no third-party
font CDN on any served page — philosophy and security compose into the same rule).
Latin subset only (English product content); the full family is re-fetchable if a
non-latin need appears.

| Family | Role (§3c) | Designer / foundry | License |
|---|---|---|---|
| Cardo | Display — Didone / engraved-plate (Dir. A) | David J. Perry | OFL-1.1 |
| Cormorant | Display — Didone / Garamond-descended (Dir. A) | Christian Thalmann · Catharsis Fonts | OFL-1.1 |
| Zilla Slab | Display — refined slab / streamliner (Dir. B) | Typotheque · Mozilla | OFL-1.1 |
| Newsreader | Body — reading serif (leader) | Production Type | OFL-1.1 |
| Source Serif 4 | Body — reading serif | Frank Grießhammer · Adobe | OFL-1.1 |
| Literata | Body — reading serif | TypeTogether | OFL-1.1 |
| IBM Plex Mono | Mono — industrial-warm (leader) | Mike Abbink · Bold Monday · IBM | OFL-1.1 |
| JetBrains Mono | Mono | Philipp Nurullin · JetBrains | OFL-1.1 |
| Courier Prime | Mono — typewriter / receipt | Alan Dague-Greene · Quote-Unquote Apps | OFL-1.1 |

Source: Google Fonts (fonts.googleapis.com CSS2 API → fonts.gstatic.com woff2), fetched
at build time; the served page references only these local files. The OFL copyright +
license strings travel inside each `.woff2` name table; OFL-1.1.txt (this directory)
carries the license per the OFL bundling requirement.

Machine manifest: `_fonts-manifest.json` (slug · family · role · variant · file · bytes).
