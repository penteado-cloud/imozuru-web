# imozuru-web

The website for [Imozuru](https://github.com/penteado-cloud/imozuru), served by GitHub Pages at
<https://imozuru.joaopenteado.com>.

| Page | Source |
|---|---|
| `/` | landing page |
| `/privacy/` | `PRIVACY.md` in the app repo; keep the wording identical, it matches the App Privacy answers |
| `/support/` | "Support page" in the app repo's `docs/app-store.md`; the Japanese is a draft (`REVIEW (ja)`) |

Plain HTML and CSS: no build step, no web fonts, no analytics. Colours come from `imozuru/Theme.swift`;
the icons are exported from the app's `AppIcon` set (concept B in `design/icon/`).
Paths are root-relative, so the site only works at the custom domain, not at `*.github.io/imozuru-web/`.

Preview locally:

```bash
python3 -m http.server 8000
```
