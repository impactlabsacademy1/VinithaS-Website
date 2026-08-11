# Vinitha Subbhuraam — personal site

Static site, no build step. `index.html` is the whole thing.

## 1. Add your images

I couldn't fetch these automatically (they live on your old WordPress site,
which my sandbox can't reach). Right-click → "Save image as..." each one below,
and save it into the `images/` folder using the **exact filename** shown —
the HTML already points at these paths.

| Save as               | Source URL |
|---|---|
| `images/portrait.jpg` | https://vinithasubbhuraam.wordpress.com/wp-content/uploads/2025/09/cropped-vinitha.jpg |
| `images/note-code-dependent.jpg` | https://vinithasubbhuraam.wordpress.com/wp-content/uploads/2025/09/0c0ee-code-dependent.jpg |
| `images/note-ces2025.png` | https://vinithasubbhuraam.wordpress.com/wp-content/uploads/2025/09/e14fe-ces2025.png |
| `images/note-heart-brain.png` | https://vinithasubbhuraam.wordpress.com/wp-content/uploads/2025/09/df0b9-heart-brain-1.png |
| `images/book1.jpg` | https://vinithasubbhuraam.wordpress.com/wp-content/uploads/2025/09/book3.jpg |
| `images/book2.jpg` | https://vinithasubbhuraam.wordpress.com/wp-content/uploads/2025/09/book2.jpg |

Tip: you can also open each source URL directly in your browser and save from there.

## 2. Deploy on GitHub Pages

1. Create a new repo (e.g. `vinitha-site`)
2. Upload `index.html` and the whole `images/` folder, keeping that folder name
3. Repo → **Settings → Pages** → Source: `main` branch, root folder → Save
4. Live at `https://<yourusername>.github.io/vinitha-site/` in a minute or two

## 3. Editing later

Everything is in `index.html` — plain HTML/CSS/JS, no framework. Edit directly
in GitHub's web UI (pencil icon) for small changes, or clone locally for bigger ones.
Any commit to `main` redeploys automatically.
