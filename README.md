# Single-Page CV

A single-page HTML résumé / CV for **Arsema Nekre**, Junior Frontend Developer — built as a solution to the [Single-Page CV](https://roadmap.sh/projects/single-page-cv) project on [roadmap.sh](https://roadmap.sh).

## About the project

This is a beginner-level project from roadmap.sh's Frontend track. The goal is to lay out a CV — education, skills, and career history — using only semantic HTML, with no styling yet (styling comes in a later project in the series).

## Project requirements

| Requirement | Status |
|---|---|
| Semantic HTML structure | ✅ Done — `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<nav>`, `<address>` |
| Single-page layout with education, skills, and career history sections | ✅ Done |
| SEO meta tags in the `<head>` | ✅ Done — `description`, `author`, `keywords` |
| Open Graph (OG) tags for social sharing | ✅ Done — `og:title`, `og:description`, `og:type`, `og:url`, `og:image`, `og:locale` |
| Favicon linked in the `<head>` | ✅ Done — inline SVG favicon, no external file needed |

## Contents

| Section | Details |
|---|---|
| Profile | Name, title, address, phone |
| Skills | HTML5, CSS3, JavaScript (ES6+), Figma |
| Education | Adama Science and Technology University — BSc in Computer Science (2018–2022) |
| Experience | Lersha — Frontend Developer Intern (June–August 2022) |
| Links | LinkedIn and GitHub |

## File structure

```
Single-cv/
└── cv.html   # the entire CV — single self-contained HTML file
```

## Usage

### View it locally

Clone the repo and open the file directly in your browser:

```bash
git clone https://github.com/Wave-eer/Single-cv.git
cd Single-cv
```

Then open `cv.html` in any browser (double-click it, or run):

```bash
open cv.html      # macOS
start cv.html     # Windows
xdg-open cv.html  # Linux
```

### Host it online

Since it's a static HTML file, you can publish it for free with:

- **GitHub Pages** — enable Pages in the repo settings (Settings → Pages) pointing to the `CV` branch, then visit `https://wave-eer.github.io/Single-cv/cv.html`
- **Netlify / Vercel** — drag and drop the file or connect the repo

## Tech stack

- HTML5 only — no CSS framework, JavaScript, or external dependencies (styling is intentionally deferred to a follow-up roadmap.sh project)

## License

No license has been specified for this repository.

## Author

**Arsema Nekre**
- LinkedIn: [linkedin.com/in/arsema-nekre](https://linkedin.com/in/arsema-nekre)
- GitHub: [github.com/arsemanekre](https://github.com/arsemanekre)
