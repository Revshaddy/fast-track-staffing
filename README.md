# Fast Track Staffing Agency website

Responsive one-page site for Fast Track Staffing Agency (healthcare staffing, New Jersey).

## Files
- `index.html` — the whole site (HTML, CSS and JavaScript in one file)
- `assets/logo.png` — full-color logo (header)
- `assets/logo-white.png` — white logo (footer, dark mode)

## Swapping placeholder images
1. Upload your photos into the `assets` folder (e.g. `assets/hero.jpg`).
2. In `index.html`, find a placeholder such as:
   `<div class="ph"><span>Hero image</span></div>`
3. Replace it with:
   `<img src="assets/hero.jpg" alt="Describe the photo" style="border-radius:20px;width:100%;height:100%;object-fit:cover">`

## To-do before launch
- Connect the contact form to a form service (e.g. Formspree) — it currently only shows a confirmation.
- Add real links for social icons, Terms & Conditions and Privacy Policy.
- Confirm the "1090 section" tax form name (likely 1099 or W-9).
