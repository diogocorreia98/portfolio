# My Portfolio

Personal portfolio website for me, **Diogo Correia**, a data engineer focused on **Python, SQL, AWS, telemetry pipelines, data quality, and analytics-ready platform design**.

This repository contains the source for a static portfolio site that highlights:

- current data engineering positioning and experience
- an updated downloadable resume
- featured portfolio projects
- certifications, impact metrics, and contact links

## Overview

The site is built as a lightweight static webpage and customized from the Start Bootstrap Freelancer theme. It has been updated to better reflect a data engineering profile instead of the original starter-template structure.

Current sections include:

- **Hero**: personal brand, core stack, and headline impact metrics
- **Featured Work**: portfolio cards and detailed project modals
- **Highlights**: current role, measurable impact, certifications, and tooling
- **About**: summary and career focus
- **Footer**: direct contact, LinkedIn, and GitHub links

## Featured Projects

### Tire Fleet Telemetry Pipeline

Lead project currently featured on the site.

Highlights:

- end-to-end telemetry pipeline case study
- parquet ingestion and quality validation workflow
- fleet analytics and inactivity detection
- dimensional warehouse design with fact and dimension modeling
- based on a repository with 16.8M+ raw events and 49.2K validated tire-day aggregates

Repository:

- https://github.com/diogocorreia98/tire-fleet-telemetry-pipeline

### Dungeon Escape

Secondary project kept on the site as a gameplay prototype example.

## Tech Stack

- HTML5
- CSS3
- Bootstrap 5
- Font Awesome
- Google Fonts

No build step is required for local viewing.

## Project Structure

```text
portfolio/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── scripts.js
├── assets/
│   ├── docs/
│   │   └── DiogoCorreiaCV-2026.pdf
│   ├── favicon.ico
│   └── img/
│       ├── avataaars.svg
│       └── portfolio/
│           ├── cabin.png
│           └── telemetry-pipeline.svg
└── README.md
```

## Running Locally

Because this is a static site, you can open it directly in a browser:

```bash
open index.html
```

Or serve it locally with Python:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Updating Content

The main content lives in:

- `index.html` for page copy, links, sections, and project modals
- `css/styles.css` for theme styling and layout customization

Resume asset:

- `assets/docs/DiogoCorreiaCV-2026.pdf`

Featured project artwork:

- `assets/img/portfolio/telemetry-pipeline.svg`

## Customization Notes

This portfolio is intentionally simple to maintain:

- add or remove project cards directly in `index.html`
- update project visuals in `assets/img/portfolio/`
- replace the resume PDF in `assets/docs/`
- adjust branding, spacing, and colors in `css/styles.css`

## Contact

- Email: `diogoc1608@gmail.com`
- LinkedIn: https://www.linkedin.com/in/diogodata/
- GitHub: https://github.com/diogocorreia98

## License

Personal portfolio source based on the Start Bootstrap Freelancer theme. Review upstream theme licensing if you plan to reuse the template commercially.
