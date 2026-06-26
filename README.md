# Sourish Dutta Portfolio — Static GitHub Version

This folder is a plain static website. It does **not** need Bun, npm, React, Lovable, Vite, build configuration, or dependencies.

## Files

- `index.html` — the complete website with all HTML, CSS, and JavaScript included in one file.
- `.nojekyll` — keeps GitHub Pages from processing the site with Jekyll.

## Run locally

Open `index.html` directly in your browser.

Optional local server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Upload to GitHub

1. Create a new GitHub repository.
2. Upload `index.html`, `.nojekyll`, and this `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Save.

Your site will be available at:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```
