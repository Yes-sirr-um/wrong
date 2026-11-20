# The Way We Rise and Fall

A single-page, aesthetic web story with a lip red theme.

## Structure

```
aesthetic-site/
├── index.html          # Self-contained site: HTML, CSS, script, and all images embedded
├── README.md
└── images/             # Original image assets (source copies, not needed to run the site)
    ├── painting-1.png
    ├── painting-2.png
    ├── painting-3.png
    ├── prologue-1.png
    └── prologue-2.png
```

## Running locally

Open `index.html` in any modern browser. No other files are needed, since the images are embedded.

## Notes

- No build step or dependencies. Fonts fall back to Georgia and Helvetica Neue.
- Sections fade in on scroll; this is disabled automatically when the visitor prefers reduced motion.
- Colors are set with CSS variables in the `:root` block at the top of the `<style>` section.
- Images are embedded as JPEG data URIs, resized to a maximum of 1200px on the longest side.
