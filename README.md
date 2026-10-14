# Amal Webcraft Portfolio

This is a lightweight static portfolio website for **Amal Webcraft** (formerly Iyyad Webcraft). It is built with plain HTML and Tailwind CSS via CDN, requiring no build step or Node.js dependencies.

## Features
- Responsive, mobile‑first design using the specified colour palette and typography.
- Accessible navigation with a fully‑keyboard‑operable mobile menu.
- Hero section with clear value proposition and primary/secondary CTAs.
- Trust & value bullets.
- Selected work showcase (Maison Café – live link, EstatePro – placeholder URL).
- Services overview with three service cards.
- Clear 4‑step process.
- About section with concise copy.
- FAQ accordion using native `<details>` elements for accessibility.
- Contact section with WhatsApp, email placeholders and a simple inquiry form (client‑side placeholder handling).
- Footer with navigation links and dynamic current year.
- Motion respects `prefers-reduced-motion`.
- SEO‑friendly meta tags, favicon, and semantic HTML structure.

## Running locally
Since this is a static site you can serve it with any static HTTP server. Examples:

### Python
```bash
python -m http.server 3000
```
Then open `http://localhost:3000` in your browser.

### Node (optional)
If you prefer a Node server, install a tiny static server:
```bash
npm install -g serve
serve -l 3000
```

## Customisation
- **Colors & fonts** – Adjust the Tailwind config block at the top of `index.html`.
- **Brand information** – Edit the wordmark, meta description, and footer text.
- **Contact details** – Email and phone links are functional, and the contact and reservation forms are Netlify‑enabled. After deploying to Netlify, enable form handling in the Netlify UI and set up email notifications to receive submissions at `afailaliyyad4@gmail.com`.
- **Project URLs** – Provide the real URL for EstatePro (replace `#` link) and add any additional projects.
- **Images** – Swap the placeholder images (`https://via.placeholder.com/...`) with real screenshots, placing them in an `assets/` folder and updating the `src` attributes.

## Deployment
The site consists of a single `index.html` (and optional assets). Deploy by uploading the file to any static hosting provider (Vercel, Netlify, GitHub Pages, etc.). No build step required.

**Important**: Verify that all contact information and form configurations are correct before launch.

---
Generated with 🤖 [Claude Code](https://claude.com/claude-code)
