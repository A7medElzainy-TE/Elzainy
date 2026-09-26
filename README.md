# Ahmed Elzainy — Portfolio

A lightweight, production-ready static portfolio focused on internal tools and support operations projects.

## What changed from the original

- Rebuilt the page as a polished single-page portfolio with clear visual hierarchy.
- Replaced hidden tab content with semantic sections and anchor navigation for better SEO and usability.
- Added responsive layouts for desktop, tablet, and mobile.
- Added dark/light theme support with saved user preference.
- Added accessible focus states, skip navigation, reduced-motion support, semantic landmarks, and descriptive labels.
- Added project detail cards, capability sections, approach/process, and a stronger contact CTA.
- Removed third-party font dependency to reduce requests and improve privacy/performance.
- Optimized the portrait image and added WebP with JPEG fallback.
- Added metadata, Open Graph basics, JSON-LD structured data, favicon, web manifest, and robots.txt.
- Kept the project framework-free: plain HTML, CSS, and JavaScript for fast loading and simple GitHub Pages deployment.

## Deploy on GitHub Pages

1. Push all files in this folder to the root of the repository.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch (usually `main`) and `/ (root)`.
5. Save.

## Customize

- Project content: `index.html`
- Styling: `assets/css/styles.css`
- Theme/navigation behavior: `assets/js/main.js`
- Profile photo: replace `assets/images/ahmed.jpg` and `assets/images/ahmed.webp`
- Contact details: search in `index.html` for the email and phone number.

## Performance notes

The portfolio intentionally avoids frameworks, icon libraries, analytics, and remote fonts. This minimizes JavaScript, requests, and third-party dependencies while keeping the source easy to maintain.
