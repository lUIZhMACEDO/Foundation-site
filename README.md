# Al King III Foundation Website

Static website for the Al King III Foundation.

## Local Preview

Open `index.html` directly in your browser or use a simple server:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

## Publish on GitHub Pages

1. Create a new public repository on GitHub named `al-king-iii-foundation` (or your preferred name).
2. On your computer, inside this folder, initialize Git and push:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Al King III Foundation site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```
3. In GitHub, go to Settings → Pages.
4. Under "Build and deployment", set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` and folder `/root`
5. Save. Wait 1–2 minutes. Your site will be live at:
   `https://<your-username>.github.io/<your-repo>/`

### Custom domain (optional)

1. In Settings → Pages, add your custom domain.
2. Create DNS CNAME record pointing to `<your-username>.github.io`.
3. Commit a `CNAME` file at repo root containing only your domain name.

## Assets

- Logo: `assets/Al King Logo.png` is displayed in the navbar.

## Edit and Deploy

Each time you commit to `main`, GitHub Pages updates automatically.


