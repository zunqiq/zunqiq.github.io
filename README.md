# Zunqi Li's Academic Homepage

A plain English academic homepage for biography, research interests, education, academic service and publications.

## Pages

- `index.html`: homepage
- `profile.jpg`: profile photo used on the homepage
- `publications.html`: publication list
- `publication-01.html`: example correction / clarification detail page

## Local preview

Run this in the project directory:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages

Upload the files to a GitHub repository and configure **Settings → Pages → Deploy from a branch**, using the `main` branch and the root directory. No build step is required.

## Replace before publishing

- The placeholder publication titles, authors, venues and years in `publications.html`.
- The correction details in `publication-01.html`.
- Any personal profile wording you want to refine.
