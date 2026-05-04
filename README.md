# qishao11.github.io

Personal homepage. Hand-coded HTML, modeled after [zhengchunran.com](https://zhengchunran.com/). Tailwind via CDN, FontAwesome 4.7 via CDN, no build step.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

GitHub Pages auto-publishes `main` to https://qishao11.github.io after every push.

## Customize

- `index.html` — content (bio, news, Featured Research, Academic Service)
- `stylesheet.css` — navbar + layout (loaded first)
- `styles.css` — reserved for overrides
- `images/profile.jpg` — your photo (square or 1:1.2 portrait recommended; falls back to grey block if missing)
- `images/mags_slam.jpg` — paper teaser (16:9 recommended)
- `cv.pdf` — drop your CV here

To replace the placeholder profile image, just drop a JPG at `images/profile.jpg` and `git push`.
