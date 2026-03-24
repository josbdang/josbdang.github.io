# Personal Academic Website

Personal website of **Dr. Joseph Binh Thanh Dang** — Senior Lecturer, School of Information Technology, Whitecliffe College, Wellington, New Zealand.

## Live Site

[https://josbdang.github.io](https://josbdang.github.io)

## Technology

- **Bootstrap 5.3.8** — Responsive grid, components, and utilities (CDN)
- **jQuery 3.7** — Smooth scrolling, scroll interactions (CDN)
- **Bootstrap Icons** — Iconography (CDN)
- **Google Fonts** — Libre Baskerville (display) + Source Sans 3 (body)

All styles are embedded in `index.html` — single file, no build tools, no external CSS dependencies.

## Setup

1. Create a GitHub repository named `josbdang.github.io`
2. Clone it locally:
   ```bash
   git clone https://github.com/josbdang/josbdang.github.io.git
   cd josbdang.github.io
   ```
3. Copy `index.html` and this `README.md` into the repository folder
4. (Optional) Add a profile photo as `photo.jpg` and update the `<img>` tag in the hero section
5. Commit and push:
   ```bash
   git add .
   git commit -m "Update personal website"
   git push origin main
   ```
6. Visit **Settings → Pages** and confirm the source is set to deploy from the `main` branch
7. Site will be live within a few minutes at `https://josbdang.github.io`

## Customisation

| What                     | Where                                                              |
|--------------------------|--------------------------------------------------------------------|
| Colours & fonts          | Edit the CSS variables in `:root` inside the `<style>` block      |
| Personal details & text  | Edit the HTML content directly                                     |
| Profile photo            | Replace the placeholder `<img>` src in the hero section            |
| Contact links            | Update `href` values in the `#contact` section                     |
| Google Scholar / ORCID   | Replace the `#` placeholder hrefs with your actual profile URLs    |
| Publications             | Add/remove `.pub-entry` blocks in the `#publications` section      |

## Site Structure

- **About Me** — Background, research statement, career history
- **Research Interests** — Six areas: Combinatorial Optimisation, Explainable AI in Healthcare, Applied ML & NLP, Software Engineering Analytics, Nature-Inspired Computation, IoT & Network Optimisation
- **Publications** — Published and accepted works only (journals, book chapters, conference papers)
- **Teaching & Supervision** — Courses, evaluation scores, postgraduate supervision outcomes
- **Professional Service** — Committee roles, advisory positions, peer review, memberships, community
- **Contact** — Email, Google Scholar, ORCID, GitHub

## Licence

Content © 2026 Dr. Joseph Binh Thanh Dang. Code structure freely reusable.
