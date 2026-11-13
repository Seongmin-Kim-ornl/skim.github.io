# Seongmin Kim: personal homepage

A single-file academic homepage. Everything (HTML, CSS, JavaScript) lives in `index.html`; there is no build step.

## Publish on GitHub Pages

1. Create a public repository named `<your-username>.github.io`.
2. Upload `index.html` (and this README) to the repository root.
3. Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io`.

## Edit the content

- **Publications**: edit the `PUBS` list near the bottom of `index.html`. Each paper is one line. Add `u:"https://doi.org/..."` to make a title clickable.
- **Profile links** (Google Scholar, CV PDF, GitHub, LinkedIn): uncomment and fill in the example buttons in the hero section. To offer a CV download, put the PDF in the repository root and link to its file name.
- **Everything else** (positions, talks, awards, service, contact): plain HTML in clearly commented sections.
- **Colors and fonts**: the variables at the top of the `<style>` block.
