# Sakhawat Hossain Portfolio

A fast, ATS-friendly, static portfolio built with pure HTML, CSS, Bootstrap, and JavaScript. Hosted on GitHub Pages.

## Stack
- HTML + CSS
- Bootstrap 5
- JavaScript (dark/light toggle)
- Static assets in `public/`

## Project Structure
- `index.html` Main page (all content)
- `public/resume.pdf` Resume placeholder
- `public/og.png` OpenGraph image placeholder
- `public/favicon.svg` Favicon placeholder
- `.github/workflows/deploy.yml` Optional GitHub Actions workflow (can be removed for static branch deploy)

## Run Locally
Option 1: Open `index.html` directly in your browser.

Option 2: Run a simple static server:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

## Edit Content
All content is in `index.html`. Update the following areas as needed:
- Hero text and CTA links
- Projects section (add/remove cards)
- Skills, experience, and certifications
- Contact details
- Footer “Last updated” date

## Deploy (GitHub Pages)
This is a `username.github.io` repo, so no build step is required and the base path is `/`.

1. Commit and push to `main`:
```bash
git add .
git commit -m "Update portfolio"
git push origin main
```
2. GitHub Pages settings:
- Source: **Deploy from a branch**
- Branch: `main`
- Folder: `/` (root)

## Optional: GitHub Actions
If you prefer GitHub Actions deployment, keep `.github/workflows/deploy.yml` and set Pages source to **GitHub Actions**.
If you prefer branch deploy, you can delete `.github/workflows/deploy.yml`.

## Notes
- Contact form uses `mailto:` only, no backend required.
- Replace `public/resume.pdf` and `public/og.png` with your real files.

## License
Personal portfolio content.
