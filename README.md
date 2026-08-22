# BlitzPay — website

Public marketing site for BlitzPay, served via GitHub Pages.

**This repository is public.** It contains only the landing page and its image
assets. No payroll data, client files, or source code belong here — those live
in the separate private prototype repository.

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

Opening `index.html` directly from the filesystem will not load the logo or
favicon, because relative paths need a real base URL to resolve against.

## Deploying

Pushing to `main` publishes automatically via GitHub Pages
(Settings → Pages → Deploy from a branch → `main` → `/root`).
