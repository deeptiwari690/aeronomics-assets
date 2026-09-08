# Aeronomics Assets

Static assets for Aeronomics.

## Current use

Hosts the company logo (`aeronomics_logo.png`) as a publicly accessible image URL, referenced inside the auto-generated quote email template (Zoho CRM Deluge function `getQuoteHtmlTemplate`). Email clients like Gmail don't reliably render inline SVG or base64-embedded images, so the logo needs to be hosted at a stable public URL instead.

## Status

This is a temporary hosting solution. Once the Aeronomics website (Next.js, deployed on Vercel) is built, this asset should move into that project's own `public/` folder, and the image URL referenced in the Zoho function should be updated accordingly.
