# Sakhawat Hossain Portfolio

A fast, ATS-friendly, static portfolio built with pure HTML, CSS, Bootstrap, and JavaScript. Hosted on GitHub Pages.

## Tech
- HTML + CSS
- Bootstrap 5
- JavaScript (theme toggle)
- Static assets in `public/`

## Run Locally
Open `index.html` directly in the browser or use a simple static server.

Example with Python:
```bash
python -m http.server 8000
```

## Edit Content
All content is in:
- `index.html`

Resume placeholder:
- `public/resume.pdf`

## Deploy (GitHub Pages)
For `username.github.io`, no build step is required.

1. Push to `main`:
```bash
git add .
git commit -m "Update portfolio"
git push origin main
```
2. In GitHub, set Pages source to **Deploy from a branch** and select `main` / root.

## Notes
- OpenGraph image placeholder: `public/og.png`
- Favicon placeholder: `public/favicon.svg`
- Mail contact form uses `mailto:` (no backend required)

## License
Personal portfolio content.
