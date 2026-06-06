# My Website

A clean, modern, fully responsive website starter — no frameworks, no dependencies.

## File Structure

```
website/
├── index.html        ← Main HTML (all sections)
├── css/
│   └── style.css     ← All styles (variables, layout, responsive)
├── js/
│   └── main.js       ← Nav toggle, scroll animations, form handling
├── images/           ← Put your images here
└── README.md
```

## Sections

| Section   | ID          | Description                        |
|-----------|-------------|------------------------------------|
| Navbar    | —           | Fixed top nav with mobile toggle   |
| Hero      | `#home`     | Full-screen intro with CTA buttons |
| About     | `#about`    | Two-column text + stats layout     |
| Services  | `#services` | Three-card feature grid            |
| Contact   | `#contact`  | Simple contact form                |
| Footer    | —           | Minimal copyright footer           |

## Customisation

1. **Colors** — Edit CSS variables at the top of `style.css`
2. **Fonts** — Swap the Google Fonts link in `index.html` and update `--font-display` / `--font-body`
3. **Content** — Edit text directly in `index.html`
4. **Form** — Replace the `contactForm` submit handler in `main.js` with your backend/API call

## Getting Started

Just open `index.html` in a browser — no build step required.