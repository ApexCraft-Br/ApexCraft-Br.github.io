# ApexCraft public hub

Static GitHub Pages site for **ApexCraft** (org `ApexCraft-Br`).

Live origin: <https://apexcraft-br.github.io/>

This is the company portfolio, short product cards, and the **canonical privacy-policy host** for Play Console / App Store / in-app legal links.

## Pages deploy

GitHub Pages publishes from **`/` on `main`** (org user site). No `/docs` source. HTTPS is provided by `github.io`.

Do **not** enable Pages on the private product monorepos (`tiny-wins`, `our-finances`, `ac-starter-mobile`).

## URL map (stable)

| Path | Role |
|------|------|
| `/` | ApexCraft portfolio (Portuguese default) |
| `/en/` | English portfolio |
| `/apps/tiny-wins/` | Tiny Wins short product card |
| `/en/apps/tiny-wins/` | Tiny Wins card (English) |
| `/privacy/tiny-wins/` | **Play Console + in-app policy URL — do not rename** |
| `/en/privacy/tiny-wins/` | Same policy, English default |
| `/privacy/` | Privacy index |
| `/apps/our-finances/` | Stub card (product not in stores yet) |

### Canonical Tiny Wins policy

`https://apexcraft-br.github.io/privacy/tiny-wins/`

That path is bilingual (pt-BR + en) on one HTML document. Play / App Store fields must keep this URL. If a custom domain is added later, **keep the `github.io` paths as redirects** so store listings do not 404.

Never point store privacy fields at `github.com/.../blob/.../PRIVACY.md`.

## Languages

Portuguese is the default. English is one tap away via mirrored `/en/` paths. The Tiny Wins policy also honors `?lang=en` / `?lang=pt` on the canonical URL.

## Contact

Privacy contact is the studio inbox `apexcraft@googlegroups.com`.

## Out of scope

This repo is static HTML + CSS. It is **not** the full Tiny Wins marketing landing (that stays in `ApexCraft-Br/tiny-wins`). Do not copy private app source here.
