# Brandgrowth Agency Pvt. Ltd.

Static website with seven dedicated service pages.

## Upload to GitHub
1. Extract this ZIP.
2. Create a repository named brandgrowth.
3. Choose Add file > Upload files.
4. Upload the extracted dist folder, vercel.json and README.md together at the repository root. Do not upload the ZIP itself.
5. Commit changes.

## Vercel
Import the GitHub repository. Use Framework Preset: Other, Root Directory: repository root, Build Command: empty, Output Directory: dist. The included vercel.json sets the static output directory and trailing-slash routing.

Add brandgrowth.online and www.brandgrowth.online in Project Settings > Domains. Make brandgrowth.online the primary domain and redirect www to it. Follow the exact DNS instructions shown by Vercel.

SEO canonical URLs, sitemap and social URLs use https://brandgrowth.online. Update these if you choose another primary domain.

Vercel Hobby is for personal, non-commercial use. Use an eligible plan for this business website.

## Notes
The enquiry form opens an email draft; it does not send emails or save enquiries on a server. Fonts load from Google Fonts. Animated examples are illustrative, not client results. Browser/device visual testing is still required before launch.

## Local preview
From the dist folder run: python3 -m http.server 8000
Then visit http://localhost:8000.
