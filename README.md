# Ahmed Elzainy — Portfolio

A clean, lightweight static portfolio focused on internal tools and support operations.

## Features

- Single-page layout with clear sections: Hero, Work, About, Process, Contact
- Dark / light theme with saved preference
- Mobile-friendly navigation (hamburger menu)
- Accessible: skip link, focus states, reduced-motion support
- No frameworks, no external fonts, no analytics
- Optimized static portrait
- SEO basics: meta description, Open Graph, JSON-LD, favicon, web manifest

## Deploy on GitHub Pages

1. Push all files in this folder to the root of the repository.
2. In GitHub: **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch (usually `main`) and `/ (root)`.
5. Save.

## Customize

| What | Where |
|------|--------|
| Content | `index.html` |
| Styles | `assets/css/styles.css` |
| Theme / nav / animations | `assets/js/main.js` |
| Photo | Replace `assets/images/ahmed.jpg` |
| Email / phone | Search in `index.html` |

## Design principles

- Simple hierarchy and generous spacing
- System font stack for speed and privacy
- Minimal motion, respects `prefers-reduced-motion`
- Works well on mobile without extra libraries
