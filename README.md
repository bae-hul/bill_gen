# Bill Number Stamper

Single-file tool that stamps up to 6 four-digit bill numbers onto the Sai Abhay Petroleum bill template and downloads the result as a PDF. The numbers are baked into the page image (not selectable text) with a scanned-ink look.

## Deploy on GitHub Pages

1. Create a repository and upload `index.html` (this whole folder works too).
2. Repo **Settings → Pages → Source: Deploy from a branch**, pick `main` and `/ (root)`, save.
3. Open `https://<username>.github.io/<repo>/` — done.

No build step, no dependencies to install. The page pulls `pdf-lib` from a CDN, so it needs an internet connection to load.

## Use

Type up to 6 numbers (4 digits each; blanks are skipped), check the live preview, hit **Generate PDF**.
