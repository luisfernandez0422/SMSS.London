# London 2027 — GitHub Pages website

A responsive, static website based on the supplied UTRGV study abroad poster, with an integrated illustrated hero and accessible HTML headline. No installation, build process, API keys, or external fonts are required.

## Publish on GitHub Pages

1. Create a GitHub repository (or use your existing website repository).
2. Upload the **contents** of this folder to the repository root: `index.html`, `styles.css`, `.nojekyll`, and the complete `assets` folder. Keep the `assets` folder structure intact.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`, and save.
5. GitHub will display your website address when the deployment is ready.

All local links use relative paths, so this works at either a user site or a repository site URL. You can also open `index.html` directly to preview locally.

## Edit the website

- Change program text and links in `index.html`.
- Change colors, spacing, and typography in `styles.css`.
- Replace `assets/poster.png` to update the poster.
- The Apply Now button links to https://utrgv.via-trm.com/program_brochure/39034. Email links are configured for `luis.fernandez01@utrgv.edu`.

Program facts come from the supplied poster. Exact dates, costs, eligibility, financial support, and itinerary have not been invented; the page directs questions to Dr. Fernández. The contact buttons launch the visitor's email app; there is no form submission service.

## Artwork

The website uses the supplied original illustrations unchanged. Transparent PNGs are individually positioned with responsive CSS. JPEG illustrations keep their original blue backgrounds. No regenerated artwork is used. All nine supplied illustrations are included in `assets`; the crown is available for future use. The original program poster is preserved as well.

The hero title uses the supplied original logo at `assets/program-logo.png`, with an accessible text alternative.

## Newsletter signup

The Get London 2027 updates section links to the supplied Microsoft Form in a new tab. Responses are handled by Microsoft Forms, not stored by this website. Email delivery and notifications when the website changes are not automated by this signup link.
