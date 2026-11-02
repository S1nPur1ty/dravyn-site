# Dravyn downloads

Live: https://dravyn-six.vercel.app

A small, accessible, dependency-free download page for the Dravyn macOS preview.

- Source: `public/index.html` and `public/style.css`
- Static assets: `public/assets/`
- Hosting: Vercel, linked to this GitHub repository
- Downloads: GitHub Releases in `S1nPur1ty/Dravyn`

Preview locally with `python3 -m http.server 8080 --directory public`.
To update a release, change the version, requirements, download URL and release-notes
URL together in `public/index.html`. Assets are hosted in GitHub Releases, not in Git.
There are no cookies, analytics, accounts, or client-side JavaScript.

The dragon artwork is the existing Dravyn brand asset. Source was created with AI assistance.
