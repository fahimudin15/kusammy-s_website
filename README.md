# Kusammy’s Store — Beauty & Fashion Boutique

A simple, fast, and mobile‑first landing site for Kusammy’s Store with two category pages:
- Cosmetics & Skin Care (beauty.html)
- Thrifts & Fashion (fashion.html)

Built with HTML + Tailwind CSS (CDN) and a tiny JS file for interactivity.

## Project Structure
- index.html — Landing page (Hero, About, Services, Contact)
- beauty.html — Cosmetics & Skin Care listing (product grid with local images)
- fashion.html — Thrifts & Fashion listing
- assets/js/main.js — Mobile menu, on‑scroll reveals, footer year
- assets/images/beauty — Local product images for Beauty page
- assets/ — Place favicon.ico and og.jpg here if available

## Quick Start
1. Open index.html directly in your browser.
2. For best results, use a simple local server (e.g., VS Code Live Server) to browse pages and assets.

## Adding Product Images (Beauty Page)
- Put images in: assets/images/beauty
- Filenames are used as product names in beauty.html
- Example: assets/images/beauty/Abana Facial cream.jpg

If you add more images and want them listed:
- Tell your assistant the filenames and short descriptions, or
- Duplicate one of the existing product cards in beauty.html and change:
  - img src
  - product title (h3)
  - description text
  - the WhatsApp link message text

## WhatsApp Inquire Buttons
- Each product “Inquire” button deep‑links to WhatsApp with a prefilled message using phone: +2349065221101.
- To change the number, search for `wa.me/2349065221101` in beauty.html (and other pages if needed) and replace with your number.

## Tailwind & Styling
- Tailwind is loaded via CDN in each HTML file. No build step required.
- Custom palette: blush, cream, gold. Fonts: Poppins (display) and Inter (sans).

## SEO & Assets
- Update meta tags in index.html for description, og:image, and favicon.
- Place favicon.ico and og.jpg in assets/ and update paths if different.

## Deployment
- Any static host works (Netlify, Vercel, GitHub Pages, etc.).
- Ensure your images are included in assets/images/beauty.

## Notes
- When opening files directly (without a server), prefer relative paths like `assets/...` (already set).
- If images don’t show, verify the exact filenames and that they exist in the expected folder.
