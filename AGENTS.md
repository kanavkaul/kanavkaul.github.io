# PersonalWebsite — AGENTS.md

## Stack
- Vanilla HTML5 + CSS3 + JavaScript (no frameworks, no bundler)
- Google Fonts (Inter) via CDN in `index.html`
- No package.json, no build step, no tests, no linting

## Serve locally
Open `index.html` in a browser — no server required.

## Deploy
Push `main` to GitHub; GitHub Pages serves the site from the root of the `main` branch (configured in repo Settings > Pages).

## Architecture notes
- **CSS theming**: All colors/spacing in `:root` variables in `styles.css`
- **Navigation**: JS in `script.js` handles smooth scrolling and active-link highlighting on scroll
- **Animations**: `IntersectionObserver` fades in `.timeline-item`, `.skill-category`, `.project-card`, `.education-item` on scroll (opacity 0→1, translateY 20px→0)
- **No client-side routing** — single-page anchor navigation only
- Mobile breakpoints at 768px and 480px

## Content editing
- `index.html` contains all content (experience, skills, education, contact)
- Add skills as `<span class="tag">` inside `.skill-tags` divs
- Add experience items as `.timeline-item` blocks
- Project cards follow `.project-card` pattern
