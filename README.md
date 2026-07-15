# ShapeMe legal documents

Legal documents for the **ShapeMe** app. Bilingual (DE binding / EN
convenience). This folder is a self-contained static site with **clean URLs** —
each document is a folder with an `index.html`, so it serves at the
extensionless path the app links to.

```
/                → index.html      (landing)
/privacy         → privacy/index.html
/terms           → terms/index.html
/impressum       → impressum/index.html
/style.css       → style.css
CNAME            → shapeme.torchtechnology.de
```

Hosted at **https://shapeme.torchtechnology.de** (GitHub Pages, repo
`absolutebasti/shapeme-legal`). The app and the App Store Connect metadata
link to:

| URL | Serves |
|---|---|
| `https://shapeme.torchtechnology.de/privacy` | Privacy Policy |
| `https://shapeme.torchtechnology.de/terms` | Terms of Use |
| `https://shapeme.torchtechnology.de/impressum` | Legal Notice (Impressum) |

**Provider (all documents):** Finn Klapper · Amrumer Str. 16, Apartment 57 ·
13353 Berlin, Germany · finn.klapper77@gmail.com

> These documents are drafts tailored to the app's actual data processing (no
> accounts, local-only data, AI meal analysis via the Supabase proxy →
> OpenRouter/Google, hashed-IP rate limiting, Apple-only billing, local
> notifications), but they are **not a substitute for review by a qualified
> lawyer** before production launch.
