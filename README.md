# Dr. Ibrahim Torih · Executive CV

A static bilingual (Arabic / English) CV website, deployable on GitHub Pages with no additional server.

**Canonical site URL:** https://dr-torih.github.io/ibrahim-torih-cv/

## Publishing

1. Create a **public** repository named `ibrahim-torih-cv` under the GitHub user `Dr-Torih`.
2. Upload **the contents of this folder**, so `index.html` and `cv-social-preview.jpg` are at the **top level** of the repository. Keep the whole `assets/` folder.
3. In repository **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/(root)`, then **Save**.
4. After GitHub Pages is live, open the site and preview image from the URLs below.

## Checks

- Website: https://dr-torih.github.io/ibrahim-torih-cv/
- WhatsApp thumbnail image: https://dr-torih.github.io/ibrahim-torih-cv/cv-social-preview.jpg
- Meta tags: View the page source and check `og:image` (absolute HTTPS URL), `og:title`, `og:description`, and `og:url`.
- Use [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/) to request re-scraping of the new URL.
- Test **a brand-new WhatsApp message** containing only the new link.

## Maintenance

- Main file: `index.html` (includes both languages and interactive scripts).
- Images and bundled fonts: `assets/` (paths relative to repository root).
- Public image: `cv-social-preview.jpg` (1200 × 630, normal JPEG), linked in `og:image`.
- Personal photograph: `ibrahim-portrait.jpg`.
- Keep all asset filenames and structure when editing. Do not put the site inside another folder.
- If renaming the repo or adding a custom domain, update the **absolute** `og:image`, `og:url`, canonical URL and `twitter:image` in `index.html`.

This site is intentionally independent of the Trainer Studio and course repositories.
