# Dr Glo website (static, no build step)

Host: drag this folder into Netlify / Cloudflare Pages / Vercel, or upload to S3, Azure Static Web Apps, or any web host.

## Images (stored in /images; missing art falls back to built-in artwork)
Current page assets: logo.png, aesthetic-care-hero-illustrative.jpg, clear-aligner-care-illustrative.jpg, dental-consultation-illustrative.jpg, skin-treatment-illustrative.jpg, slimming-consultation-illustrative.jpg, hair-restoration-illustrative.jpg, permanent-makeup-illustrative.jpg, wellness-consultation-illustrative.jpg.

These photos are illustrative generated visuals, not photographs of the clinic or its clients. Replace them with approved clinic photography before presenting them as real people, treatments or interiors.
Before/after pairs: ba-1-before.jpg / ba-1-after.jpg ... ba-6-before.jpg / ba-6-after.jpg
Use only photos you own and, for clients, with their written consent. Use same size and framing for each pair.

## Content
Edit the SERVICES, BA and REVIEWS lists at the top of the script in index.html.
Add only genuine client reviews: entries with empty text are hidden.
"India's No. 1" claim: keep documented proof (ASCI advertising rules).

## SEO
The page includes local clinic metadata, a canonical URL, social sharing tags, structured business information, `robots.txt` and `sitemap.xml`. If the production domain changes, update the URLs in `index.html`, `robots.txt` and `sitemap.xml`.
