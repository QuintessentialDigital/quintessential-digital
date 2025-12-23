# Quintessential Digital — Website

A professional one-page website for https://www.quintessentialdigital.com/

## Files
- `index.html` — main page
- `styles.css` — styling
- `robots.txt` — crawler rules
- `sitemap.xml` — sitemap

## Deploy via GitHub Pages
1) Create a new GitHub repo (e.g., `quintessentialdigital-site`)
2) Upload these files to the repo root
3) GitHub → Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `(root)`
4) Your site will appear on the GitHub Pages URL

## Use your custom domain
1) GitHub → Settings → Pages → Custom domain:
   - `www.quintessentialdigital.com`
2) Enable **Enforce HTTPS**
3) Add DNS records in your domain provider (see below)

### DNS (recommended)
- CNAME:
  - Host: `www`
  - Value: `<your-github-username>.github.io`

Optional (for apex redirect `quintessentialdigital.com` → `www`):
- A records for apex:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
