# 30-Day High-Protein Vegan Meal Plan — Website

Static site exported from the design canvas.

## Files
- `index.html` — landing page (every "Download File" / "Get the plan" button opens your Razorpay link: https://rzp.io/rzp/WIScISlx)
- `success.html` — thank-you page with the "Download PDF" button
- `assets/cover.png` — cover image used on the landing page
- `30-Day-High-Protein-Vegan-Meal-Plan-India.pdf` — the meal plan

## Hosting
Upload the whole folder to any static host (Netlify, Vercel, GitHub Pages, Hostinger, etc.).
To preview locally, open `index.html` in a browser.

## Before launch
- In your Razorpay Payment Page settings, set the redirect after successful payment to your hosted `success.html` URL.
- `success.html` and the PDF are public files. Anyone with the URL can download them.
  For proper payment-gated delivery, serve the PDF from a server that verifies the Razorpay payment first.
