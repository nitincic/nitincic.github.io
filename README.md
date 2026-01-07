# Personal site (GitHub Pages)

This repo is ready to publish via **GitHub Pages**.

## Quick publish (recommended)
1. Create a new GitHub repo (e.g., `nitinagrawal.github.io`).
2. Upload all files in this folder (keep the same structure).
3. In GitHub: **Settings → Pages**
   - **Build and deployment**: Deploy from a branch
   - **Branch**: `main` / `(root)`
4. Your site will appear at:
   - `https://<username>.github.io/` (for a `username.github.io` repo), or
   - `https://<username>.github.io/<repo>/` (for a normal repo)

## Local preview
Open `index.html` in your browser, or run a tiny server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Notes
- Your photo is in `assets/Nitin_Agrawal.jpg`.
- Tailwind is loaded from a CDN for simplicity. You can later switch to a build pipeline if desired.
