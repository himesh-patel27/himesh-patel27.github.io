# Himesh Patel — IT Support & Cybersecurity Portfolio

A static, responsive portfolio ready for local review or GitHub Pages. Nothing has been published.

## Preview locally

Extract the ZIP first, then open `index.html` in a modern browser. Keep the `assets` folder beside it. CSS and JavaScript are embedded in the page; project images are local, so the page does not depend on remote images, fonts, libraries, or a build system.

Alternatively, run a local static server in this folder, such as `python -m http.server 8000`, and visit `http://localhost:8000`.

## Publish to GitHub Pages when ready

1. Create or choose a GitHub repository for the portfolio.
2. Upload the contents of this folder to the repository root: `index.html`, `assets/`, `.nojekyll`, and this README. Upload the contents, rather than nesting the whole folder.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select the branch containing the files (usually `main`), select **/(root)**, and save.
5. Wait for GitHub's Pages deployment to finish, then open the URL GitHub provides. Project-site paths work because asset links are relative.

These steps publish the site publicly. This package was delivered for review only.

## Content and evidence

- All nine requested sections are included, with five featured projects and separate simulations and employment sections.
- Screenshots were downloaded from Himesh's public project repositories on October 2, 2026. `assets/sources.json` records their source URLs.
- The Splunk overview is a collage of the ten original panels rendered from the five-page dashboard PDF. It is labeled as a PDF-derived overview; the original pages and PDF are available in the project details.
- Screenshot proportions are preserved. Click an image to enlarge; use Escape or Close to dismiss. Without JavaScript, image links still open their local originals.
- Expand the About Me and individual project sections for more depth.
- The hero uses the approved professional headshot supplied by Himesh. The original photo is included locally in `assets/headshot.png`.
- Credential links and resume downloads are omitted because verified public credential URLs and final resume files were not available.
- Certification badges use text initials, not official issuer logos.
- Azure labs are identified as guided college labs, with resources decommissioned after completion.

## Editing

Edit `index.html` to update copy, dates, or links. Styles are in its `<style>` block and interactions in its final `<script>` block. Add new images to `assets/` and use relative paths. Preserve alt text, semantic headings, and the reduced-motion styles.

## Checks completed

Reviewed desktop (1440px), mobile (390px), and small mobile (320px). Automated checks found no horizontal overflow, failed page images, or JavaScript errors. Verified navigation menu, project expansion, image enlargement, Escape dismissal, and reduced-motion visibility. Desktop and mobile screenshots were visually inspected. No deployment or repository changes were performed.

## Add a resume download later

GitHub Pages can serve a resume PDF as a static file. When the final approved resume is available, place it at `assets/Himesh-Patel-Resume.pdf` and add this link alongside the hero buttons:

```html
<a class="button" href="assets/Himesh-Patel-Resume.pdf" download="Himesh-Patel-Resume.pdf">Download resume ↓</a>
```

The resume file must be uploaded together with the site. A download button is intentionally omitted until the actual final file is supplied. Anything uploaded to the public site, including a resume, is publicly accessible.
