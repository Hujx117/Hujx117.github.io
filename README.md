# Jiaxin Hu — Personal Homepage

A minimal, English-only academic homepage built with plain HTML and CSS, hosted with
GitHub Pages at **https://hujx117.github.io**.

## Structure

```
.
├── index.html          # All page content
├── assets/
│   ├── style.css       # Styles
│   ├── avatar.jpg      # Profile photo
│   └── favicon.svg     # Browser tab icon
└── README.md
```

## Editing

- **Content**: edit `index.html`. Sections are marked with comments
  (`About`, `Education`, `Research`, `Open Source`, `News`, `Contact`).
- **Colors / typography**: edit the CSS variables at the top of `assets/style.css`.
- **Photo**: replace `assets/avatar.jpg` (square image recommended).

## Local preview

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Any push to the `main` branch of `Hujx117/Hujx117.github.io` is published
automatically by GitHub Pages.
