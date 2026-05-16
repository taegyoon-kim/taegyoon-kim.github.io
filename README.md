# taegyoon-kim.github.io

Personal academic homepage. Plain static HTML + CSS, no build step.

## Structure

```
index.html       — About (homepage)
research.html    — Publications and working papers
teaching.html    — Courses
lab.html         — Knowledge and Democracy Lab
cv.html          — CV (PDF embed)
assets/
  styles.css     — Single stylesheet
  images/        — headshot.png
  files/         — cv.pdf
```

## Local preview

Open `index.html` directly, or:

```
python3 -m http.server 8000
```

## Deploy

Push to `taegyoon-kim/taegyoon-kim.github.io` on the default branch. GitHub Pages serves the files as-is — no Jekyll, no build.

## Updating

- **CV**: replace `assets/files/cv.pdf`.
- **Headshot**: replace `assets/images/headshot.png`.
- **Publications / students / courses**: edit the relevant `.html` file directly.
