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

## Domain / GitHub Pages

Repo: https://github.com/maryamahmadi-DS/childart-intellect-website  
Account login: `maryamahmadi-DS`  
Pages source: branch `main`, folder `/` (root)  
CNAME file: `www.childartintellect.com`

### If you cannot find Settings → Pages

1. Sign in as **maryamahmadi-DS** (owner). Settings 404s if you are signed into a different account.
2. Open: https://github.com/maryamahmadi-DS/childart-intellect-website/settings/pages  
   Or: Repository → **Settings** → left sidebar **Pages** (under “Code and automation”).

### Finish custom domain (required once)

GitHub API rejects the custom domain until the domain is verified on this account:

1. Open account Pages domains: https://github.com/settings/pages  
2. Under **Verified domains**, add/verify `childartintellect.com` (TXT challenge already in DNS).  
3. Return to repo Pages settings and set **Custom domain** to: `www.childartintellect.com`  
4. Wait for DNS check to succeed, then enable **Enforce HTTPS**.

Production URLs:

- https://www.childartintellect.com/
- https://www.childartintellect.com/privacy/
- https://www.childartintellect.com/terms/

Interim (already live):

- https://maryamahmadi-ds.github.io/childart-intellect-website/
