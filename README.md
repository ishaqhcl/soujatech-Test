# SuojaTech Oy Website

Static website ready to deploy on Cloudflare Pages.

## Files

- index.html
- privacy.html
- style.css
- script.js
- assets/suojatech-logo.png

## Formspree Setup

In `index.html`, replace:

```html
https://formspree.io/f/YOUR_FORM_ID
```

with your actual Formspree endpoint.

## Cloudflare Pages Deploy

1. Create a GitHub repository.
2. Upload all files from this folder.
3. Cloudflare Dashboard > Workers & Pages.
4. Create Pages project.
5. Connect your GitHub repository.
6. Framework preset: None.
7. Build command: leave blank.
8. Output directory: `/`
9. Deploy.
10. Add custom domains:
   - suojatech.com
   - www.suojatech.com
