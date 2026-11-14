# Shabrina Humairoh — Portfolio Website

A responsive personal portfolio website built with plain HTML, CSS, and JavaScript. It is designed to be hosted for free with GitHub Pages.

## Files

- `index.html` — page content and structure
- `style.css` — colors, layout, typography, and responsive styles
- `script.js` — mobile menu, project filters, reveal effects, and copyright year
- `assets/profile.jpg` — add your own profile photo here

## Before publishing

1. Replace `assets/profile.jpg` with your own portrait photo. Keep the filename exactly `profile.jpg`.
2. In `index.html`, replace `YOUR.EMAIL@example.com` with your professional email address.
3. Replace the generic GitHub, LinkedIn, project, and publication links (`https://github.com/`, `https://www.linkedin.com/`, and `href="#"`) with your real URLs.
4. Review all project, research, experience, and achievement descriptions for accuracy. Add missing dates or details where needed.
5. If a project is not public yet, link to a public report or remove the link until it is ready.

## Publish with GitHub Pages

1. Create a GitHub repository named exactly `YOUR-USERNAME.github.io`.
2. Upload the contents of this folder to the repository's root. `index.html` must be at the root, not inside another nested folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait a few minutes. Your site should appear at `https://YOUR-USERNAME.github.io`.

## Customize

- Change the palette in the `:root` section at the top of `style.css`.
- Add a new project by copying one `<article class="project-card">` inside `.projects-grid`.
- Project filter categories currently supported: `analytics`, `machine-learning`, and `forecasting`.
- Add or remove experience and research entries by copying the matching HTML blocks.

## Notes

- No build tools or paid hosting are required.
- Google Fonts are loaded from Google Fonts; the site still has fallback fonts if unavailable.
- The contact section uses a `mailto:` link. It does not submit information to a server.
