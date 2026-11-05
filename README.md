# Dot Edge Innovations — Static Website v2.5

This is the static HTML edition of the Dot Edge Innovations website, prepared for GitHub Pages, Cloudflare Pages or Netlify.

## Included
- `index.html` — Home
- `about.html` — About
- `services.html` — Services
- `products.html` — Products
- `contact.html` — Contact
- `404.html` — Not-found page

## Static-site conversion
The five original preview pages were already self-contained HTML documents with inline styles/scripts and embedded image data. They have been retained as HTML rather than rebuilt, so the existing layouts, brand assets, product cards, links, responsive styling and interactive JavaScript remain intact. The WordPress/PHP theme is intentionally not included in this static deployment package.

A restrained ambient motion layer has been added, with a reduced-motion accessibility fallback.

## Deploy on GitHub Pages
1. Extract this ZIP.
2. Upload the *contents* of this folder to the root of your GitHub repository (not the ZIP itself).
3. Ensure `index.html` is in the repository root.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select your branch (usually `main`) and folder `/ (root)`, then save.
7. Wait for GitHub Pages to publish the site.

## Contact form
The current static contact page uses the contact details and links embedded in the supplied preview. A static host cannot process PHP form submissions. If you later add an actual submission form, connect it to a form endpoint/service or your own backend.

## Important
- No WordPress/PHP runtime is required for this static version.
- External product links remain external.
- Test all pages and navigation after publishing.
