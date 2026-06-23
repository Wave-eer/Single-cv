# Single-Page CV

A single-page HTML résumé / CV for **Arsema Nekre**, Junior Frontend Developer — built as a solution to the [Single-Page CV](https://roadmap.sh/projects/single-page-cv) project on [roadmap.sh](https://roadmap.sh).

## About the project

This is a beginner-level project from roadmap.sh's Frontend track. The goal is to lay out a CV — education, skills, and career history — using only semantic HTML, with no styling yet (styling comes in a later project in the series).

## Project requirements

Per the [project brief](https://roadmap.sh/projects/single-page-cv):

| Requirement | Status |
|---|---|
| Semantic HTML structure | ⚠️ Partial — uses heading/paragraph tags, but headings are nested inside `<p>` |
| Single-page layout with education, skills, and career history sections | ✅ Done |
| SEO meta tags in the `<head>` | ❌ Not yet added |
| Open Graph (OG) tags for social sharing | ❌ Not yet added |
| Favicon linked in the `<head>` | ❌ Not yet added |

### Next steps to fully meet the brief
- Wrap each section (Profile, Skills, Education, Experience, Links) in semantic elements like `<header>`, `<section>`, and `<footer>` instead of plain `<h2>`/`<p>` tags
- Move the nested `<h2>Lersha</h2>` out of the `<p>` tag — headings can't be children of paragraphs
- Add a `<meta name="description">` tag describing the page
- Add Open Graph tags (`og:title`, `og:description`, `og:image`, `og:type`)
- Add a `<link rel="icon">` favicon

## Contents

| Section | Details |
|---|---|
| Profile | Name, title, address, phone |
| Skills | HTML, CSS, JavaScript, Figma |
| Education | Adama Science and Technology University — BSc in Computer Science (2018–2022) |
| Experience | Lersha — Frontend Developer Intern (2 months) |
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
