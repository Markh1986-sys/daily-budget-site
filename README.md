# Daily Budget marketing site

This folder is a complete static site ready to publish to GitHub Pages.

## Deploy in 5 minutes

1. Create a new public GitHub repository, e.g. `daily-budget-site`
2. From this folder, run:
   ```bash
   cd "/path/to/Daily Budget App/github-pages-site"
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/daily-budget-site.git
   git push -u origin main
   ```
3. On GitHub, go to the repo → Settings → Pages
4. Source: Deploy from a branch · Branch: `main` · Folder: `/ (root)` · Save
5. Wait 1–3 minutes. Your site will be live at `https://YOUR-USERNAME.github.io/daily-budget-site/`

## What's in here

- `index.html` — landing page with feature pitch and pricing
- `privacy.html` — privacy policy (the URL you paste into App Store Connect → App Privacy)
- `support.html` — support / FAQ page (the URL you paste into App Store Connect → Support URL)
- `_shared.css` — single stylesheet used by all three pages
- `README.md` — this file (don't worry, GitHub Pages won't serve it as a page)

## URLs you'll paste into App Store Connect

After deploying:

- **Support URL**: `https://YOUR-USERNAME.github.io/daily-budget-site/support.html`
- **Privacy Policy URL**: `https://YOUR-USERNAME.github.io/daily-budget-site/privacy.html`

Or if you want cleaner URLs, buy a domain (£10/year on Namecheap or Cloudflare) and point it at this repo. Then your URLs become:

- `https://dailybudget.app/support`
- `https://dailybudget.app/privacy`

## Updating

To change anything: edit the HTML/CSS locally, then:
```bash
git add . && git commit -m "Update copy" && git push
```
GitHub Pages will redeploy in about a minute.

## Notes

- All pages have a `<meta name="viewport">` and use system fonts, so they look right on every device.
- Dark mode is automatic via `prefers-color-scheme`.
- Year in the footer auto-updates via a tiny inline script.
- No analytics, no trackers, no third-party scripts — staying consistent with the privacy policy.
