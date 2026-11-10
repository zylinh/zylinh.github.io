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
- `assets/Zhengyuan_Lin_CV.pdf`: CV linked from the nav bar and the profile links. This must be the PUBLIC build (`CV_Zhengyuan_Lin_public.pdf`, no manuscripts under review); the CV preview server in `E:\zylin_CV` copies it here automatically.

## GitHub Pages

Repository: https://github.com/zylinh/zylinh.github.io

Website: https://zylinh.github.io/

Publish from the `main` branch, `/` (root), using **Settings → Pages → Deploy from a branch**. `.nojekyll` enables serving the static files directly.

Future updates:

```sh
git add -A
git commit -m "Update academic homepage"
git push origin main
```

