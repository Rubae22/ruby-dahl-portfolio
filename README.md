# Ruby Dahl Design — Portfolio

## File structure

```
ruby-dahl-portfolio/
├── index.html               ← Homepage
├── work.html                ← Works grid page
├── about.html               ← About + contact page
├── work-project-template.html  ← Template — duplicate for each project page
├── style.css                ← Shared styles (homepage + about)
├── README.md
└── assets/                  ← Drop all images and logo files here
    ├── logo.svg             ← Small nav logo (the "r" mark)
    ├── wordmark.svg         ← Big "Ruby Dahl Design" hero lockup
    ├── photo.jpg            ← Your photo for the about page
    ├── ocr-evade-cover.jpg
    ├── avant-garde-cover.jpg
    ├── canberras-modern-cover.jpg
    ├── majura-wine-cover.jpg
    ├── anu-inspace-cover.jpg
    ├── type-experiments-cover.jpg
    ├── smiths-cover.jpg
    ├── spec-design-cover.jpg
    ├── one-click-cover.jpg
    ├── pholish-cover.jpg
    └── emotorise-cover.jpg
```

## Adding a new project page

1. Duplicate `work-project-template.html`
2. Rename it to match the work item href in `work.html`
   e.g. `work-ocr-evade.html`
3. Update the title, tag, meta fields, body copy, and image paths inside

## Deploying to GitHub Pages

1. Create a repo named `yourusername.github.io`
2. Push the contents of this folder to the root of that repo
3. Your site will be live at `https://yourusername.github.io`

## Logo notes

- If your logo SVG is dark (black on white), add `style="filter:invert(1)"` to the `<img>` tag in the nav on `index.html` (the homepage uses a dark background)
- The works and about pages use a white background so the logo should display as-is
