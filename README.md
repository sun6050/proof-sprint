# Proof Sprint v2

Static launch prototype for a seven-day portfolio-evidence planner. It has eight job-family paths and optional job-description keyword detection. It does not upload, store, or transmit a user's inputs.

## Publish with GitHub Pages

1. Create a public repository named `proof-sprint` on GitHub.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages** in the repository.
4. Choose **Deploy from a branch**, `main`, and `/(root)`, then save.
5. GitHub will publish a URL in the form `https://YOUR-GITHUB-USERNAME.github.io/proof-sprint/`.
6. Replace both placeholders in `robots.txt` and `sitemap.xml` with that real URL before submitting the sitemap in Google Search Console.

## Important next step

This is intentionally not yet an LLM product. Do not add an API key to `index.html`. A real AI version should call a server-side endpoint where the provider key is held as a secret environment variable.
