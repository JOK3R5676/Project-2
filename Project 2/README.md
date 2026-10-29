# Project Two — Personal Website

Project Two adds separate external CSS files to the **original** Project One pages while preserving the original text, images, and HTML structure.

## File structure
- `index.html` → `index.css` (fluid width layout)
- `resume.html` → `resume.css` (fixed 960px layout on desktop, mobile adaptation)
- `aspiration.html` → `aspiration.css` (fluid width layout)
- `images/` → the four original images
- `READ.ME` → original Project One readme

Each CSS file includes a matching copy of the common navigation styling and its own six explicitly commented page-specific styles. The same navigation markup appears on every HTML page. HTML changes from Project One are limited to two-space formatting, descriptive page titles, adding the appropriate CSS link and a body class, changing the email hyperlink to `mailto:`, and removing an obsolete iframe attribute.

## GitHub Pages and Canvas submission
1. Create a new Project Two GitHub repository; upload all these files, with `index.html` and its CSS files at the repository root and the images inside `images/`.
2. Configure GitHub Pages under **Settings → Pages → Deploy from a branch**, selecting `main` and `/(root)`.
3. Open and check all three pages at the live GitHub Pages URL.
4. Validate each live HTML page at https://validator.w3.org/nu/ and each CSS file at https://jigsaw.w3.org/css-validator/. Save one HTML and one CSS validation screenshot for **each page** (six total).
5. Post the repository URL, GitHub Pages live link, and six screenshots in Canvas Project Two.

**Note:** The assignment instructions say “one ... CSS file,” but the requested revision explicitly uses three separate named CSS files, one per page. Live-site validation screenshots cannot be provided before GitHub Pages deployment.
