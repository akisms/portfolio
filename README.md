# Ayman Kotob — Work Portfolio (for BrightHire)

A single-page portfolio of product marketing work, hosted on GitHub Pages.

## Contents
- **ZapConnect enablement decks** — embedded live from Google Slides
- **RevOps assets** — Zap Map + State of RevOps Automation Report (PDFs, with in-page viewer)
- **Blogs** — published Zapier blog articles
- **Web pages** — zapier.com pages
- **Automation inspiration** — example use cases and templates

## Structure
```
index.html              # the whole site
assets/img/             # headshot + PDF thumbnails
assets/pdfs/            # the two hosted PDFs
```

## Run locally
```
python3 -m http.server 4321
# then open http://localhost:4321
```

## Publish on GitHub Pages
1. Push this folder to a GitHub repo.
2. Repo → Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. The site goes live at `https://<username>.github.io/<repo>/`.
