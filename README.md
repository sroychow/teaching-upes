# Orbit Physics

A responsive, static course-content website for undergraduate and postgraduate physics teaching.

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`. Course data can be customised in `app.js`.

## Deployment

The GitHub Actions workflow deploys the site to GitHub Pages after a push to `main`, `master`, or `work`. In the repository settings, set **Pages → Source** to **GitHub Actions**.
