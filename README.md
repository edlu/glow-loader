# Glow loader

A small static page that showcases an **SVG loading spinner** with layered glow, gradients, and a smooth “breathing” dash animation. Built with plain **HTML** and **CSS** (custom properties and `@property` for interpolating dash values).

## Run it

Open `index.html` in a browser, or serve the folder with any static server:

```bash
npx serve .
# or: python3 -m http.server 8080
```

## What’s inside

| File | Role |
|------|------|
| `index.html` | Markup and inline SVG for the spinner |
| `styles.css` | Layout, theme tokens, spinner geometry, filters, and animation |
| `type-scale.css` | Type scale utilities used by the page |
| `.vscode/` | Editor settings and recommended extensions |

Tweak the look in `styles.css` under `:root` (colors, stroke widths, glow, timing).

## Requirements

A **recent browser** that supports CSS `@property` and modern SVG/CSS features (Chrome, Edge, Firefox, Safari current versions).

