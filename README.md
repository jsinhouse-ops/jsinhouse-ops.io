# Ningchen Textile Technology – Website

Static single-page site hosted on GitHub Pages.

## Publish
1. Upload `index.html` (and this README) to the root of your repository.
2. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
3. Tick **Enforce HTTPS**.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a few minutes.

## Edit
Open `index.html` and scroll to the `EDIT HERE` section near the bottom:
- `CONFIG` – company name, email, WhatsApp, address, Formspree endpoint
- `FABRICS` – catalog cards (copy an entry to add a fabric)
- `CERTIFICATIONS` / `INSPECTION_STANDARDS` – quality section

## Quote form
Create a free form at https://formspree.io and paste the endpoint
(e.g. `https://formspree.io/f/abcdwxyz`) into `CONFIG.formEndpoint`.

## Own photos (optional)
Create an `images/` folder in the repo, upload photos, and set
`image: "images/your-photo.jpg"` on the fabric entry.
