# ChildArt Intellect website

Public legal and marketing pages for ChildArt AI.

- Privacy: `/privacy`
- Terms: `/terms`

## Stack

Static HTML/CSS (no build step). Deployed with GitHub Pages.

## Local preview

```bash
python3 -m http.server 8080
```

Open `http://127.0.0.1:8080/privacy` and `/terms`.

## Domain

Production hostnames:

- `https://www.childartintellect.com/privacy`
- `https://www.childartintellect.com/terms`

Point DNS for `www.childartintellect.com` (and optionally apex) to GitHub Pages after the domain is registered.
