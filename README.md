# The Way We Rise and Fall

A single-page, aesthetic web story with a lip red theme.

## Structure

```
aesthetic-site/
├── index.html          # Full site (HTML + inline CSS + small inline script)
├── README.md
└── images/
    ├── painting-1.png  # Hero image
    ├── painting-2.png  # Chapter I image
    ├── painting-3.png  # Chapter II image
    ├── prologue-1.png  # Prologue image (beach at sunset)
    └── prologue-2.png  # Prologue image (eyes)
```

## Running locally

Open `index.html` in any modern browser. Keep the `images/` folder beside it so the images load.

## Notes

- No build step or dependencies. Fonts fall back to Georgia and Helvetica Neue.
- Sections fade in on scroll; this is disabled automatically when the visitor prefers reduced motion.
- Colors are set with CSS variables in the `:root` block at the top of the `<style>` section.
