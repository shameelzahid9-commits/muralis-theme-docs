# Muralis theme — documentation & support site

A ready-to-publish static site for the **Muralis** Shopify theme's public
**documentation** and **support contact form** (Shopify Theme Store Requirement 21:
both must be public and linked from your theme listing).

## Files
| File | What it is |
|------|------------|
| `index.html` | Landing page linking to Documentation and Support |
| `documentation.html` | Full merchant-facing theme documentation |
| `support.html` | Support contact form (needs a Formspree endpoint) |
| `styles.css` | Shared styling |
| `muralis-logo.png`, `favicon.png` | Brand assets |
| `documentation.md` | Markdown source for the docs (optional to keep) |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## 1. Set up the contact form (Formspree — free)
1. Create a free form at https://formspree.io and copy your form endpoint
   (looks like `https://formspree.io/f/abcdwxyz`).
2. Open `support.html`, find `YOUR_FORM_ID`, and replace the whole `action` URL
   with your endpoint.
3. In Formspree, turn on the **autoresponse** so submitters get a confirmation
   email (the page promises this).

## 2. Publish with GitHub Pages (free, public)
1. Create a public repo, e.g. `muralis-labs/muralis-theme-docs`.
2. Upload every file in this folder to the repo root.
3. Repo **Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save.**
4. After a minute the pages are live at:
   - Docs:    `https://muralis-labs.github.io/muralis-theme-docs/documentation.html`
   - Support: `https://muralis-labs.github.io/muralis-theme-docs/support.html`
   - Home:    `https://muralis-labs.github.io/muralis-theme-docs/`

## 3. Wire the URLs into the theme
Send me the final Documentation and Support URLs and I'll set
`theme_documentation_url` and `theme_support_url` in `config/settings_schema.json`
(replacing the `prints4sure.com` placeholders) and rebuild the theme ZIP. Set the
same two URLs on your Partner Dashboard theme listing as well.

## Support commitments to honor (Requirement 22)
- Reply to support requests within two business days.
- Fix theme bugs (broken layouts, dead links, logic errors) promptly.
- Custom code / design / app integrations may be offered as separate paid services.
