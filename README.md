# GogitaDent — website MVP

A small static, responsive clinic website built with plain HTML, CSS and JavaScript. Ukrainian is the default language; the UA/RU switcher translates the main content.

## Files
- `index.html` — page structure, metadata and local business structured data
- `styles.css` — responsive visual styles
- `script.js` — language switcher
- Existing clinic photos in the repository root are used in the gallery and hero.

## Preview locally
Open `index.html` in a browser. No build step or package installation is required.

## Publish
The repository can be published using GitHub Pages: in repository Settings → Pages, select deployment from the `main` branch and the root folder. A custom domain can be connected later.

## Important before public launch
1. Confirm that the displayed address is exactly the clinic's public address.
2. Confirm the preferred public name: GogitaDent is used as the brand on this site.
3. Review every service label against the actual clinic service list. The service cards are intentionally generic until the official list is checked.
4. The website now includes a responsive price-list gallery using the eight original image files in `прайс/`. Each image opens in full size in a new tab; prices are not retyped, so the original clinic price sheets remain the source of truth.
5. Test phone and messaging links on an actual phone. WhatsApp links use the supplied phone numbers; Telegram links may depend on Telegram's phone-number privacy and account settings.
6. Add the final domain to canonical/Open Graph metadata and connect Google Search Console after choosing the domain.
7. Verify that each photo is the intended image and add alt text that describes the actual photo. Image file names were used because the images could not be visually inspected through the repository connector.
8. Confirm that the Schema.org business type and hours are suitable before production launch. Saturday is shown as appointment-only and Sunday as closed in visible page content.

## Confirmed contact details
- Phone / WhatsApp / Telegram: 067 713 09 13
- Phone / WhatsApp / Telegram: 067 900 54 18
- Monday–Friday: 09:00–19:00
- Saturday: by appointment
- Sunday: closed
- Address used in the page: проспект Науки, 12, Kharkiv
