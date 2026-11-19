# raphmajma.com — Literary Journal

Single-page author website for Raphael Majma, built with plain HTML and CSS. No build process, no backend, no tracking, no photography.

## Files
- `index.html`: content, metadata and navigation
- `styles.css`: layout, colors, typography and responsive design
- `.nojekyll`: tells GitHub Pages to serve files without Jekyll processing

## Preview and edit
Open `index.html` in a browser. To adjust text, edit `index.html`; for visual changes, edit `styles.css`. Fonts and the optional CSS normalization utility use public CDNs, with browser fallbacks offline.

## Deploy with GitHub Pages
1. Create a **public** GitHub repository (e.g. `raphmajma-site`).
2. Upload **the files inside this folder** into the repository root, not the enclosing folder.
3. In **Settings → Pages**, select **Deploy from a branch**, `main`, `/(root)`, and Save.
4. Test `https://YOUR-USERNAME.github.io/raphmajma-site/`.
5. In the same Pages settings, set **Custom domain** to `raphmajma.com` before configuring DNS.
6. In your domain provider's DNS, point `@` A records to GitHub Pages' documented IPs, and `www` CNAME to `YOUR-USERNAME.github.io`.
7. After DNS verification and HTTPS certificate issuance, enable **Enforce HTTPS**.

See official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site and https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Before launch
- Replace `EMAIL LINK TO BE ADDED BEFORE LAUNCH` with a real mailto link or another reliable method of contact.
- Review all copy for accuracy and final tone.
- Check mobile layout, navigation, and accessibility.
- Consider adding a canonical URL and social share image when the domain is live.
- Do not delete MX/TXT records used for email when changing web-hosting DNS.

## Licenses
The site layout and site-specific CSS are original. External dependencies:
- modern-normalize by Sindre Sorhus (MIT): https://github.com/sindresorhus/modern-normalize
- Fraunces font (SIL OFL): https://github.com/undercasetype/Fraunces
- DM Sans font (SIL OFL): https://github.com/googlefonts/dm-fonts

Retain required upstream license notices if vendor-copying any dependency into this repository.
