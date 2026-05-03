# qishao11.github.io

Personal homepage. Plain HTML/CSS, no build step.

## Local preview

```bash
cd ~/qishao11.github.io
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy to GitHub Pages

```bash
cd ~/qishao11.github.io
git init
git add .
git commit -m "init personal site"
gh repo create qishao11.github.io --public --source=. --push
```

GitHub Pages will auto-publish from `main` to `https://qishao11.github.io`.
Enable in repo settings → Pages → Source = `main` / root if not auto-enabled.

## Customize

- `index.html` — content (name, bio, news, publications, projects, CV link)
- `assets/style.css` — typography & layout
- `assets/avatar.jpg` — profile photo (140×140 square recommended; falls back to grey circle if missing)
- `assets/cv.pdf` — drop your CV here

Replace the placeholder Google Scholar / ORCID / LinkedIn / X links in
`index.html` (`href="#"`) with your real URLs.
