# sauravboloor.com

Personal website. Static HTML/CSS, no build step, no framework.

## Preview locally

```sh
cd website
python3 -m http.server 8000
```

Open http://localhost:8000.

## Deploy

Push to `main` on GitHub. GitHub Pages serves automatically.

For a root domain like `boloorsaurav.github.io`, name the repo `boloorsaurav.github.io`. For a custom domain, add a `CNAME` file with the domain and point DNS at GitHub Pages.

## Structure

- `index.html` — home (hero + socials)
- `projects/index.html` — work portfolio
- `404.html` — not-found page
- `static/css/site.css` — all styles
- `static/img/` — favicon, og-image, project thumbs
