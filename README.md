# Space Blast Privacy Policy

Public privacy policy for Space Blast. Hosted on GitHub Pages.

## Setup (3 minutes)

1. Create a new public GitHub repo called `space-blast-privacy`
   - Go to https://github.com/new
   - Repository name: `space-blast-privacy`
   - Public ✓
   - Add a README
   - Click "Create repository"

2. Push this folder to the repo:
   ```bash
   cd privacy-policy
   git init
   git add .
   git commit -m "Initial privacy policy"
   git branch -M main
   git remote add origin https://github.com/YOUR-GITHUB-USERNAME/space-blast-privacy.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Repo → Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main`, folder: `/ (root)`
   - Click Save

4. Wait ~60 seconds. Your site is live at:
   ```
   https://YOUR-GITHUB-USERNAME.github.io/space-blast-privacy/
   ```

5. (Optional) Use a custom domain:
   - Buy a domain (e.g. `spaceblast.app` for ~$15/year on Cloudflare Registrar)
   - In the repo, create a `CNAME` file with just `privacy.spaceblast.app` in it
   - In your DNS, add a CNAME record: `privacy` → `YOUR-USERNAME.github.io`
   - Enable "Enforce HTTPS" in GitHub Pages settings once the cert provisions (5-15 min)

## Required for store submission

Use this URL in:
- **Google Play Console** → App content → Privacy policy
- **App Store Connect** → App Information → Privacy Policy URL

The URL must be HTTPS — GitHub Pages provides this automatically.

## Updating

Edit `index.html`, then:
```bash
git add index.html
git commit -m "Update privacy policy"
git push
```

GitHub Pages redeploys automatically in ~30 seconds.
