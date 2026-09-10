# Run Sheets

Transport driver run sheet logger — single self-contained page, no build step,
no dependencies. Everything (run sheets, photos, settings) is stored in the
browser on the device that opened it.

## Publish on GitHub Pages

1. Create a new repository (public is fine — the app ships with no data in it).
2. Upload `index.html` and `.nojekyll` to the root of the repo.
3. Settings → Pages → Source: **Deploy from a branch**, Branch: **main**, Folder: **/ (root)**. Save.
4. Wait about a minute. The address will be:
   `https://<your-username>.github.io/<repo-name>/`

Open that address on the phone, then Add to Home Screen.

## Updating

Replace `index.html` in the repo. The address never changes, and nothing already
saved on the phone is affected.

## Setup, once per device

- **Setup → Gemini API key** — needed only for reading photos automatically.
- **Export → Email a day to work** — put the work address in once.
