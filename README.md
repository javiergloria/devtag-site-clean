# devtag-site-clean

Astro rebuild of devtag.com, migrated from the original Adobe Portfolio site.

## TODO before going live

- **Contact form**: [src/pages/contact.astro](src/pages/contact.astro) posts to Formspree with a placeholder `YOUR_FORM_ID`. Sign up at [formspree.io](https://formspree.io), create a form, and replace the ID in the `action` attribute.
- **Custom domain**: `public/CNAME` is set to `devtag.com`. Point its DNS at GitHub Pages when ready (same A/AAAA records used for the other two sites).

## Development

```
npm install
npm run dev
```
