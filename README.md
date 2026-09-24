# Alexis Carella — Resume

My personal CV and portfolio website, hosted at [alexis-devops.github.io/resume](https://alexis-devops.github.io/resume/).

Built with the [Start Bootstrap Resume](https://startbootstrap.com/theme/resume) theme (v7.0.6).

## Features

- **Bilingual** (EN/FR) — language auto-detected from browser, toggle button top-right
- **JSON-driven content** — no hardcoded text in HTML, both languages loaded from `data/resume-{lang}.json`
- **Sections**: About, Experience, Education (with professional training), Skills, Interests, Certifications, Projects

## Stack

- HTML + CSS (Bootstrap 5)
- Font Awesome, Google Fonts
- GitHub Pages

## Structure

```
data/
  resume-en.json    — English content
  resume-fr.json    — French content
index.html          — Main CV page (JSON-driven)
projects/index.html — Projects page (JSON-driven)
cv.html             — ATS-optimised standalone CV (not JSON-driven)
css/styles.css      — Main stylesheet
css/cv.css          — ATS CV stylesheet
js/scripts.js       — Bootstrap enhancements
assets/             — Images, favicon
```