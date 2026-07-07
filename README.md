# nhgamdi.com

Personal site of **Nasser Alghamdi** — teaching assistant, University of Bisha, Saudi Arabia.

- `index.html` — the entire site, self-contained (fonts, photo, and styles embedded). No build step.
- `.nojekyll` — tells GitHub Pages to serve files as-is.

## Deploy (GitHub Pages)

1. Create a public repo named `nhgamdi.github.io` (or any repo).
2. Upload these files to the repo root.
3. Settings → Pages → Source: **Deploy from a branch** → `main` / root.
4. Settings → Pages → Custom domain: `nhgamdi.com`, then enable **Enforce HTTPS** once the certificate is issued.

## DNS (at your registrar)

- `A` records for `nhgamdi.com` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- `CNAME` record for `www` → `nhgamdi.github.io`
