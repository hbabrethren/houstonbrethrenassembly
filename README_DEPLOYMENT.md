# Houston Brethren Assembly — SEO-ready deployment package

This package is built from the uploaded `index(1).html` and keeps the visible website content intact. The changes are additive technical SEO, local discovery, structured data, image optimization, accessibility attributes, crawler files, and deployment helpers.

## Files to upload to the website root

Upload every file in this folder to the public root of `https://houstonbrethrenassembly.com/`:

- `index.html`
- `building1.jpeg`
- `building1-640.jpeg`
- `building1-1024.jpeg`
- `location.jpeg`
- `location-640.jpeg`
- `og-image.jpg`
- `favicon.svg`
- `favicon-16x16.png`
- `favicon-32x32.png`
- `apple-touch-icon.png`
- `icon-192.png`
- `icon-512.png`
- `site.webmanifest`
- `robots.txt`
- `sitemap.xml`
- `_redirects` and `_headers` for Netlify / Cloudflare Pages-style static hosting
- `.htaccess` for Apache/cPanel hosting
- `llms.txt` for AI/answer-engine discovery support

## Domain note

The canonical domain is set to:

`https://houstonbrethrenassembly.com/`

If the final domain is different, replace `https://houstonbrethrenassembly.com/` in `index.html`, `sitemap.xml`, `robots.txt`, `.htaccess`, and `llms.txt` before publishing.

## What was added

- Canonical URL and hreflang tags
- Index/follow robot directives
- Local geo metadata for Pearland, TX
- Open Graph and Twitter social preview cards
- JSON-LD structured data graph for Church / ReligiousOrganization, WebSite, WebPage, ImageObject, and navigation
- Image sitemap entries
- Responsive image `srcset`, image dimensions, and descriptive alt text
- Generated favicon, app icons, and manifest
- Robots and sitemap files
- Legacy redirects for old WordPress-like paths so `/contact/`, `/our-meetings/`, `/statement-of-faith/`, and related pages point to the correct single-page sections
- Hosting headers for caching and security basics

## After deployment

1. Open `https://houstonbrethrenassembly.com/` and confirm the page renders correctly.
2. Open `https://houstonbrethrenassembly.com/robots.txt` and `https://houstonbrethrenassembly.com/sitemap.xml`.
3. Submit `sitemap.xml` in Google Search Console and Bing Webmaster Tools.
4. Use Google Rich Results Test / Schema Markup Validator to verify structured data.
5. Verify or update Google Business Profile and Bing Places using the exact same NAP:
   - Houston Brethren Assembly
   - 2880 Broadway Bend Dr., Pearland, TX 77584 - Building 1
   - hbabrethren@gmail.com
6. Keep the same address, email, and service-time wording consistent anywhere the assembly is listed online.
