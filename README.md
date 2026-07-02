# CA Deepak V Sharma & Associates — Website

A static, production-ready website for CA Deepak V Sharma & Associates (Chartered Accountants, New Delhi). Pure HTML/CSS/JS — no build step, no backend, no dependencies to install.

## Files

- `index.html` — all page content, SEO meta tags, Open Graph tags, and structured data (JSON-LD)
- `style.css` — full styling (mobile-first, responsive)
- `script.js` — navbar, mobile menu, scroll reveal, animated counters, testimonial carousel, FAQ accordion, appointment form → WhatsApp
- `favicon.svg` — site favicon

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `ca-deepak-sharma-website`).
2. Add these four files to the root of the repository (or push this folder as-is).
3. Commit and push to the `main` branch.
4. In the repository, go to **Settings → Pages**.
5. Under **Build and deployment → Source**, select **Deploy from a branch**.
6. Choose branch `main` and folder `/ (root)`, then **Save**.
7. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

No further configuration is required — there is no build process, package.json, or server component.

## Before going live — things to double-check

- **Testimonials**: the four testimonials in the Testimonials section are illustrative examples written to match the firm's public 5.0/128 review profile, not verbatim quotes from named reviewers. Swap in real client testimonials (with permission) before launch, or leave a short note that they're representative.
- **Email address**: `contact@cadeepakvsharma.com` is a placeholder — replace it with the firm's real email in `index.html` (search for `mailto:`) if different.
- **Canonical/OG URLs**: `index.html` uses `https://www.cadeepakvsharma.com/` as a placeholder domain in the `<link rel="canonical">` and Open Graph tags — update these once the site has a real domain (or a `github.io` URL).
- **og:image**: add a real `og-image.png` (1200×630px recommended) to the repo root and update the `og:image` tag, or remove the tag if you'd rather not set one yet.
- **Google Maps embed**: the map uses the free `output=embed` URL format (no API key needed) pointed at the firm's address — verify it pins the correct location once live.

## Browser support

Built with standard, well-supported CSS and JS (Flexbox, Grid, `IntersectionObserver`, CSS custom properties) — works in all current versions of Chrome, Edge, Firefox, and Safari, on desktop and mobile.
