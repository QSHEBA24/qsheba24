# QSHEBA24 — Static site

This repo contains a simple static landing page for QSHEBA24 (UGC & Video Advertising).

What's included
- index.html — accessible, responsive homepage
- styles.css — modular stylesheet with CSS variables and responsive rules

Local preview
1. Clone the repo
2. Open `index.html` in your browser or serve with a static server:
   - Python 3: `python -m http.server 8000` then visit `http://localhost:8000`
   - Node: `npx serve .`

Deployment (GitHub Pages)
1. Commit and push the files to the `main` branch (or any branch).
2. In repository Settings → Pages, set the source to the `main` branch and `/ (root)`.
3. Wait a minute and your site will be available at `https://<your-username>.github.io/<repo>/` (or the custom domain if configured).

Next steps I can help with
- Add your real images and favicon and update Open Graph images.
- Wire the contact form to a real backend (Formspree, Netlify Forms, or serverless endpoint).
- Add analytics, cookie-consent, or A/B testing snippets.
- Improve accessibility further (contrast testing, keyboard-only navigation audit).

Replace the placeholder Formspree action (`https://formspree.io/f/your-form-id`) with your Formspree form ID or remove the form if you prefer mailto only.