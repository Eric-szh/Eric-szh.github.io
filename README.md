# Personal website

Static single-page site for Zenghui (Eric) Sun. No build step, no framework.

```
index.html   page content
style.css    styling (light/dark via prefers-color-scheme)
assets/      photo.jpg, Zenghui_Sun_Resume.pdf
```

## Preview locally

```
python -m http.server 8000
```

then open http://localhost:8000.

## Deploy to GitHub Pages

1. Create a repo named `Eric-szh.github.io` on GitHub.
2. `git remote add origin https://github.com/Eric-szh/Eric-szh.github.io.git`
3. `git push -u origin main`
4. Settings > Pages > Source: Deploy from a branch, branch `main`, folder `/ (root)`.

The site is then live at https://eric-szh.github.io.

## Keeping it in sync with the resume

Content is copied from `../job application/resumes/base/experience_bank.md` and the
current `MLE_General_Resume.pdf`. When the resume changes, update the matching section
here and re-copy the PDF into `assets/`.
