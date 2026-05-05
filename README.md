# SpeakWell Coaching Website

A static marketing site for public speaking and speech competition tutoring.

## Files

- `index.html` - page content and structure
- `styles.css` - responsive layout and visual design
- `script.js` - mobile navigation, header state, and current year

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish

This site is configured for GitHub Pages using the workflow in
`.github/workflows/deploy-pages.yml`.

After the publishing setup is merged into `main`:

1. Open the repository settings in GitHub.
2. Go to **Pages**.
3. Set **Build and deployment** to **GitHub Actions** if it is not already selected.
4. The `Deploy site to GitHub Pages` workflow will publish the site from `main`.

GitHub will show the public site URL in the Pages settings once the first deployment succeeds.
