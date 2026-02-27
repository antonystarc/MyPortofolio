# My Portofolio

This repository hosts a simple static portfolio site generated from information in your resume. To make it your own, follow the steps below and replace placeholder text in `index.html` with details from your resume PDF.

## Getting Started

1. **Place your resume:**
   - Save or move your resume PDF into the root of this repository as `resume.pdf`.
   - The home page already links to `resume.pdf` for download.

2. **Edit content:**
   - Open `index.html` and search for `<!-- TODO` or other comments to find areas where you should fill in your name, tagline, projects, etc.
   - You can reuse sections of text from your resume (experience, education, skills) to populate the About and Projects sections.

3. **Projects:**
   - Add one `<div class="project">` block per project with a title, description, tech stack, and links.
   - You can link to deployed demos or GitHub repos.

4. **Contact details:**
   - Update the email, LinkedIn, GitHub, or other contact info in the Contact section.
   - The contact form simply creates a mailto link; you can replace it with a form handler or remove it.

5. **Style & customize:**
   - Feel free to modify `css/style.css` or replace it with your own design.
   - Add images under `assets/` (create that directory) and reference them from HTML if desired.

6. **Deploy:**
   - You can host this on GitHub Pages by enabling Pages for the `main` branch or any branch. A GitHub Actions workflow (`.github/workflows/gh-pages.yml`) is already included and will publish the site automatically when you push to `main`.
   - Alternatively use Netlify, Vercel, or any static hosting; just point to the root directory.

## Adding More Pages

If you'd like to expand the portfolio (blog, case studies, additional pages), create new HTML files and add links in the navigation bar.

---

The current scaffold is intentionally minimal; the goal is to make it easy to customize using your resume as the source of truth. Good luck building your portfolio!