# Pulse - Cash Flow Manager

Official landing page for the Pulse personal bookkeeping app.

## Pages

- `index.html` - product landing page
- `privacy.html` - privacy policy for App Store review
- `support.html` - support and FAQ page
- `guide.html` - basic user guide

## Local Preview

Because this is a static GitHub Pages site, you can open `index.html` directly in a browser.

For a closer production-like preview, run:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

## GitHub Pages Verification

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the branch, usually `main`, and the folder `/root`.
6. Click `Save`.
7. Wait for GitHub Pages to publish the site.
8. Open the generated URL, usually:

```text
https://<your-github-username>.github.io/<repository-name>/
```

For App Store Connect, use the published URLs for:

- Marketing URL: the homepage URL
- Privacy Policy URL: `https://<your-github-username>.github.io/<repository-name>/privacy.html`
- Support URL: `https://<your-github-username>.github.io/<repository-name>/support.html`

Support emails are sent to `tara_indy_consulting@icloud.com`.
