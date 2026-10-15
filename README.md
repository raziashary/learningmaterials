# Learning Materials

A small static library of HTML study guides, published with GitHub Pages.

## Publish

In the repository's **Settings → Pages**, set **Source** to **Deploy from a branch**, then choose **main** and **/(root)**. The site will be available at <https://raziashary.github.io/learningmaterials/> after GitHub finishes publishing. The `.nojekyll` file keeps the existing HTML files unchanged during publishing.

## Add a guide

1. Copy the standalone HTML file into `htmls/`.
2. Add a card in `index.html` with a relative `href` to the new file. Update the guide count.
3. Preview `index.html` locally and check the new link, then commit and push the changes to `main`.

Only files in this repository are published. The original learning folders beside this repository stay local.

The four converted research guides in `htmls/` are standalone HTML pages with project-specific material removed. Their original Markdown source files are not published here. Pages with equations load MathJax from jsDelivr; the text remains readable if that script is unavailable.
