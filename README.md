# Personal Academic Website

Personal website of **Dr. Joseph (Jos) Binh Thanh Dang** — Senior Lecturer and Research Coordinator, School of Information Technology, Whitecliffe College, Wellington, New Zealand.

## Live Site

🔗 [https://YOUR_USERNAME.github.io](https://YOUR_USERNAME.github.io)

## Technology

- **Bootstrap 5.3** — Responsive grid, components, and utilities (CDN)
- **jQuery 3.7** — Smooth scrolling, scroll animations (CDN)
- **Bootstrap Icons** — Iconography (CDN)
- **Google Fonts** — Libre Baskerville (display) + Source Sans 3 (body)

No build tools required. All dependencies are loaded via CDN.

## Setup

1. Create a GitHub repository named `YOUR_USERNAME.github.io`
2. Clone it locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   cd YOUR_USERNAME.github.io
   ```
3. Copy `index.html`, `style.css`, and this `README.md` into the repository folder
4. (Optional) Add a profile photo as `photo.jpg` and update the `<img>` tag in `index.html`
5. Commit and push:
   ```bash
   git add .
   git commit -m "Initial personal website"
   git push origin main
   ```
6. Visit **Settings → Pages** and confirm the source is set to deploy from the `main` branch
7. Your site will be live within a few minutes at `https://YOUR_USERNAME.github.io`

## Customisation

| What                     | Where                                                       |
|--------------------------|-------------------------------------------------------------|
| Personal details & text  | `index.html` — edit the HTML content directly               |
| Colours & fonts          | `style.css` — modify the CSS variables in `:root`           |
| Profile photo            | Replace the placeholder `<img>` src in the hero section     |
| Contact links            | Update `href` values in the `#contact` section              |
| Publications             | Add/remove `.pub-entry` blocks in the `#publications` section |

## Licence

Content © 2026 Dr. Joseph (Jos) Binh Thanh Dang. Code structure freely reusable.
