# Sachin Bhatt — Portfolio

Personal portfolio of **Sachin Bhatt**, B.Tech CSE (AI/ML) student and Software Developer building web applications, Android apps, and AI-powered tools.

**Live site:** [ADD LIVE URL]

## Highlights

- Dark, minimal design with a giant outline/solid name hero
- Background-removed portrait that rises into view, stays greyscale, reveals real colour under the cursor (touch supported), and moves with a scroll parallax
- Animated letter reveals, custom cursor, magnetic buttons, scroll-triggered reveals, animated timeline
- Animated OMR scan mockup for the computer-vision project
- Fully responsive (desktop, tablet, mobile) with an animated full-screen mobile menu
- Respects `prefers-reduced-motion`
- SEO ready: meta tags, Open Graph, Twitter cards, JSON-LD, `robots.txt`, `sitemap.xml`

## Sections

Hero · About · Experience · Featured Projects · Tech Stack · AI/ML · Currently Exploring · Resume · Contact

## Featured projects

- **Edu Portal**: PHP, MySQL, JavaScript, Bootstrap
- **Automated OMR Evaluator**: Python, OpenCV
- **Mind Power University Mobile App**: Android Studio, Java, WebView
- **MPU Track**: React, Node.js, Socket.io, MySQL, Android WebView

## Tech

Plain **HTML5, CSS3 and vanilla JavaScript**. No frameworks, no build step, no dependencies.
Fonts: Bricolage Grotesque and DM Sans (Google Fonts).

## Project structure

```
sachin-portfolio/
├── index.html          # the whole site (HTML + CSS + JS)
├── photo-cutout.webp   # background-removed hero portrait (loaded by index.html)
├── images/             # project screenshots (edu-portal.jpg, etc.)
├── resume.pdf          # add your resume here
├── robots.txt
├── sitemap.xml
└── README.md
```

## Run locally

```bash
git clone https://github.com/sachin-cyber904/<repo-name>.git
cd <repo-name>
# open index.html in your browser, or serve it:
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customize

All content lives in the script at the bottom of `index.html`, under `EDIT YOUR CONTENT HERE`:

| What | Where |
| --- | --- |
| LinkedIn link | `LINKEDIN` constant |
| Experience cards | `experience` array |
| Projects (tech, features, GitHub/demo links) | `projects` array |
| Project screenshot | `img` field, e.g. `img:"images/edu-portal.jpg"` (put files in `images/`) |
| Tech stack categories | `stack` object |
| "Currently exploring" items | `exploring` array |

Also update:

- `resume.pdf` in the project root
- `YOUR-DOMAIN.com` in `robots.txt` and `sitemap.xml`
- `og:image` in the `<head>` of `index.html`

## Deploy

Works on any static host: GitHub Pages, Netlify, Vercel, or Hostinger. Upload the folder as-is.

**GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root.

## Contact

- Email: sachinbhatt865@gmail.com
- GitHub: [github.com/sachin-cyber904](https://github.com/sachin-cyber904)
- LinkedIn: [ADD LINK]

## License

© 2026 Sachin Bhatt. All rights reserved. Please don't copy the personal content or photo; feel free to take inspiration from the structure.
