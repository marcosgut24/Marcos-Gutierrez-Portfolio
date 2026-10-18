# Marcos Gutierrez Portfolio

A responsive personal portfolio built with HTML, CSS, and JavaScript. No build tools or dependencies required.

## Run locally

From this repository:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

Open the site on port 3000. Stop the server with Ctrl+C.

## Resume

The site links to `Marcos-Gutierrez-Resume.pdf` from the introduction, navigation, and footer. Replace that file to update the resume while preserving its links.

## Customize

- Edit `index.html` to update the introduction, biography, project descriptions, and contact link.
- Education and project summaries are based on the supplied resume.
- Edit `portfolio.css` for colors, typography, and responsive layouts.
- The design uses system fonts and works without external font services.

## Publish

This static site can be hosted with GitHub Pages. After the files are pushed to GitHub, choose **Settings → Pages → Deploy from a branch**, then select your branch and the root folder.

## Profile photo

The introduction reserves a space for a portrait. Add your photo as `assets/profile.jpg`, then change the portrait image source in `index.html` from `assets/profile-placeholder.svg` to `assets/profile.jpg` and update its alt text. The photo automatically fits the layout.

The stylesheet has a unique filename and version to avoid loading styling from earlier designs. Project drawings are illustrative diagrams, not photos of the actual prototypes.
