# Rngamanch — Creative Marketing Agency

A responsive, single-page website for Rngamanch, a creative marketing agency based in Morang, Koshi Province, Nepal.

## Included

- `index.html` — complete website (HTML, CSS, and JavaScript are self-contained)
- `assets/` — folder reserved for images, icons, and other static assets
- `404.html` — lightweight not-found page for GitHub Pages
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing
- `LICENSE` — MIT license template (update the copyright holder if needed)

## Before publishing: update contact details

The current HTML contains placeholder contact information. Open `index.html` and find this line:

```js
const C={phone:"+977 98XXXXXXXX",wa:"97798XXXXXXXX",email:"hello@example.com"};
```

Replace it with the real business contact details:

- `phone`: public phone number displayed on the page
- `wa`: WhatsApp number using country code and digits only (for Nepal, start with `977`; do not include `+`, spaces, or dashes)
- `email`: business email address

Example format only (not a real contact):

```js
const C={phone:"+977 98XXXXXXXX",wa:"97798XXXXXXXX",email:"hello@example.com"};
```

Also review the page title, description, service wording, and any claims before going live. The contact form opens WhatsApp and prepares an email; it does not store submissions on a server.

## Publish with GitHub Pages

1. Create or sign in to a GitHub account at https://github.com/.
2. Create a **public** repository, for example `rngamanch-website`.
3. Extract this ZIP on your computer.
4. Upload the contents of this folder to the **root** of the repository. Make sure `index.html` is at the repository root, not inside an extra nested folder.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then save.
8. Wait for GitHub Pages to finish deploying. The published URL will appear in the Pages settings. A project site usually looks like `https://YOUR-USERNAME.github.io/rngamanch-website/`.

## Updating the website

Edit `index.html`, commit/push the changes, and GitHub Pages will publish the update automatically.

## Assets

The current site draws its logo as inline SVG and loads Figtree/Syne fonts from Google Fonts. No external image files are required for the current design. Put future images, favicons, screenshots, or other static resources in `assets/` and reference them with paths such as `assets/hero.jpg`.

## Notes

- GitHub Pages hosts static files. This site does not need a build step or Node.js.
- The WhatsApp and email links depend on the contact values being configured correctly.
- Consider adding a custom domain later in **Settings → Pages** if you own one.
