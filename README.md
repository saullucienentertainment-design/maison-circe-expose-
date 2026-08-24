# Maison Circé — Cahier d’Investigation Nº 47

**Ghost Circuits & Synthetic Lore**  
*Enquête · Souterrains Numériques · Menace Structurelle*

Static long-form investigative page published under the fictional imprint **Maison Circé** (Paris, est. 1978).

This repository is self-contained. Drop it into any GitHub (or GitLab / Codeberg) account and serve the root as a static site (GitHub Pages, Netlify, Cloudflare Pages, etc.).

---

## Structure

```
maison-circe-expose/
├── index.html                 # Main article
├── README.md
├── .gitignore
└── assets/
    ├── css/
    │   └── main.css           # All layout & typography
    └── svg/
        ├── logo-monogram.svg  # Primary circular mark
        ├── logo-wordmark.svg  # MAISON CIRCÉ wordmark
        ├── logo-footer.svg    # Light version for dark footer
        ├── ornament-rule.svg  # Decorative rule with node
        └── icon-alert.svg     # Security-box icon
```

No build step. No dependencies beyond the three Google Fonts loaded in the `<head>`.

---

## Local preview

```bash
# from the repo root
python3 -m http.server 8080
# then open http://localhost:8080
```

Or simply open `index.html` in a browser (fonts will still load from Google).

---

## GitHub Pages

1. Push this folder as a repository.
2. Settings → Pages → Source: Deploy from branch `main` / root.
3. Site will be live at `https://<user>.github.io/<repo>/`.

---

## Design notes

- **Typography**: Cormorant Garamond (display), EB Garamond (body), Outfit (UI labels).
- **Palette**: ivory paper `#fffcf7`, deep ink `#1a1a1c`, muted gold `#b8975a` / `#8c6d3a`, burgundy accent `#5c2e2e`.
- All logos and ornaments are original SVG; no external image hosts required.
- Responsive two-column layout collapses cleanly below 760 px.

---

## Content disclaimer

The article is a work of speculative investigative fiction framed as a cultural-security exposé. Public historical reference points (1994 Rome Labs, Citibank transfers, BT data exposure, contemporary aiu.fm community) are used only as atmospheric context. No public record establishes the identity “NadaProb” or proves continuous operational control by any single individual across the claimed period.

© 2026 Maison Circé — fictional imprint for this project.
