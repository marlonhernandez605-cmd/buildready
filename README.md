# BuildReady — PC Building Guide

A four-page HTML and CSS website about understanding, assembling, and planning a custom desktop PC. Created for CIT 384 Project 1.

## Live website

**Before submitting:** replace the text below with the actual URL shown in your repository's **Settings → Pages** after deployment. Do not submit this README with the placeholder still present.

Live site: **ADD YOUR GITHUB PAGES URL HERE**

## Open locally

Extract the ZIP, then open `index.html` in Chrome. All styles and images are included locally. No install, build command, external library, or JavaScript is required. You can also open the folder in VS Code and use Live Server.

## Pages and files

| File | Purpose |
| --- | --- |
| `index.html` | Home and introduction to the hobby |
| `components.html` | Eight component categories and compatibility considerations |
| `building.html` | Assembly overview, firmware setup, and troubleshooting |
| `planner.html` | Illustrative budget table, temporary worksheet, and checklist |
| `css/style.css` | Shared styles, layouts, focus states, and responsive adjustments |
| `images/` | Included original SVG illustrations and favicon |

The worksheet and checkboxes work as native browser controls. They do not save, transmit, or calculate data. The reset button resets the worksheet. The $1,200 budget is illustrative; it is not a live quote or a product recommendation.

## MDN exploration

The six features below have explanatory HTML comments at their implementation sites. They did not appear as claimed in the supplied sign-up screenshots, and searches of the supplied Weeks 1–3 lecture text found no instruction on them. Screenshots and text extraction cannot establish the live sign-up status or spoken lecture coverage. Verify availability and claim them in the class document.

| Feature | Location | Practical use | MDN documentation |
| --- | --- | --- | --- |
| `<kbd>` element | `building.html`, first-boot section | Identifies the keys used to enter firmware setup | https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/kbd |
| `<legend>` element | `planner.html`, worksheet | Captions the build-preferences fieldset | https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/legend |
| `<tfoot>` element | `planner.html`, budget table | Groups the total allocation row | https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/tfoot |
| `rowspan` attribute | `planner.html`, category header cells | Groups components under shared categories | https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/td#rowspan |
| `headers` attribute | `planner.html`, table cells | Connects cells to their heading IDs | https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/td#headers |
| `step` attribute | `planner.html`, budget input | Sets $50 increments from a minimum of zero | https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Attributes/step |

## Publish on GitHub Pages

1. Create a GitHub repository for the project.
2. Upload the **contents** of this folder so `index.html`, the other HTML files, `README.md`, `css/`, and `images/` are at the repository root. Do not upload only the ZIP, or nest the website inside an extra folder.
3. Commit the files to the `main` branch.
4. Go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then `main` and `/ (root)`. Save.
5. Wait for deployment to finish. Copy the actual website URL from that Pages screen.
6. Replace the live-site placeholder near the top of this README with that URL and commit the change.
7. Open the deployed website in Chrome and test all four navigation links.
8. Submit the **GitHub repository URL** on Canvas. The supplied assignment screenshot also asks you to sign up for a presentation.

Official deployment guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Before submission

- [ ] Claim the three elements and three attributes in the class sign-up document, with MDN links.
- [ ] Check presentation sign-up requirements.
- [ ] Review and understand the HTML and CSS.
- [ ] Confirm your instructor permits the assistance used: this draft was generated with AI assistance, while the supplied assignment prohibits automated CSS generation and calls for manual authorship. It cannot be represented as meeting that requirement without instructor approval.
- [ ] Test the four pages in Chrome and inspect images, navigation, and controls.
- [ ] Publish on GitHub Pages and replace the README's live-site placeholder.
- [ ] Submit the repository link on Canvas by the deadline.
