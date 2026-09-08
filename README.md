# Zhengyuan Lin

Academic homepage: introduction, research interests, and publications.

Static HTML/CSS with local SVG icons. No build step or JavaScript dependencies.

## Preview

```sh
python3 -m http.server 8000
```

Open http://localhost:8000.

## Edit

- `index.html`: biography, research statement, and publication citations.
- `style.css`: layout and responsive styles.
- `assets/favicon.svg`: site icon.

The portrait area is intentionally blank. The local portrait and CV PDF are excluded from Git because neither is used by the page.

## GitHub Pages

Repository: https://github.com/zylinh/zylinh.github.io

Website: https://zylinh.github.io/

Publish from the `main` branch, `/` (root), using **Settings → Pages → Deploy from a branch**. `.nojekyll` enables serving the static files directly.

Future updates:

```sh
git add index.html style.css assets/favicon.svg README.md .gitignore .nojekyll
git commit -m "Update academic homepage"
git push origin main
```

