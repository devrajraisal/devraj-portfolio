# Devraj Raisal Portfolio

A cinematic, single page portfolio for a frontend developer and React specialist. The site is built as one static HTML file with no build step, so it loads fast and can be hosted anywhere.

Live site: https://devrajraisal.dev

## What is on the page

The page is split into eight sections that you can scroll through:

- Hero
- About
- Experience
- Projects
- Skills
- Achievements
- Certifications
- Contact

## How it is built

- Plain HTML, CSS, and JavaScript in a single `index.html` file
- GSAP with the ScrollTrigger and TextPlugin add-ons for scroll driven animation and text effects
- Three.js for the interactive 3D background
- Google Fonts: Bebas Neue, DM Sans, and JetBrains Mono

All libraries are loaded from a CDN, so there is nothing to install.

## Run it locally

1. Clone the repository:
   ```bash
   git clone https://github.com/devrajraisal/devraj-portfolio.git
   cd devraj-portfolio
   ```
2. Open `index.html` in your browser, or serve the folder with any static server:
   ```bash
   npx serve .
   ```

## Deployment

The `CNAME` file points the site to the custom domain `devrajraisal.dev`. It works with GitHub Pages or any static host.

## License

Released under the MIT License. See the `LICENSE` file for details.
