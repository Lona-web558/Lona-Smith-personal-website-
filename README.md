# Lona-Smith-personal-website-

# Lona Smith — Personal Brand Site

A single-file, dark-luxury personal portfolio site for Lona Smith — Founder, Software Engineer, Content Creator, Author, Writer, Gold Investor, Billionaire, Property Owner, and Maybach Owner, based in Bryanston, Sandton, South Africa.

## Overview

This is a static, single-page HTML site built to introduce Lona Smith and showcase her ventures. It's designed as a personal brand landing page — the kind of site linked from social bios, business cards, and pitch decks.

## Features

- **Custom cursor** — gold dot + ring cursor that scales on hover over interactive elements
- **Animated hero section** — staggered fade-up entrance animations for name, title, and quote
- **Live date & time** — nav bar clock synced to Africa/Johannesburg (SAST)
- **Scroll-reveal sections** — About, Ventures, Philosophy, and Contact fade in via IntersectionObserver
- **Ventures grid** — showcases Gold Fundamentals, Business News Hub, LFashionwear, and Lona Smith Fitness
- **Philosophy quote block** — full-width styled blockquote with oversized decorative quotation mark
- **Fully responsive** — collapses to single-column layout with adjusted spacing below 768px

## Tech Stack

- Plain HTML5 + CSS3 (no build step, no frameworks)
- Vanilla JavaScript (cursor tracking, live clock, scroll reveal)
- Google Fonts: Playfair Display (serif headings) + DM Sans + DM Mono
- Zero dependencies, zero external JS libraries

## File Structure

```
lona-smith.html   → single-file site (HTML + CSS + JS inline)
README.md         → this file
```

## Sections

| Section | ID | Purpose |
|---|---|---|
| Nav | — | Fixed logo, links, live SAST clock |
| Hero | `#hero` | Name, roles, location, opening quote |
| About | `#about` | Bio + stat highlights |
| Ventures | `#ventures` | 4-card grid of active businesses |
| Philosophy | `#philosophy` | Signature quote, centered |
| Contact | `#contact` | Email, phone, TikTok + brand list |
| Footer | — | Copyright, location |

## Customization

- **Colors**: edit the CSS custom properties in `:root` (`--gold`, `--dark`, `--cream`, etc.)
- **Roles/eyebrow text**: edit `.hero-eyebrow` content in the HTML
- **Quote**: update the `.hero-slogan` and `.philosophy-quote` blockquotes
- **Ventures**: duplicate a `.venture-card` block inside `.ventures-grid` to add more

## Deployment

Since this is a single static HTML file with no dependencies, it can be deployed directly to:

- **Neocities** — drag and drop upload
- **Netlify** — drag and drop or connect via GitHub
- **GitHub Pages** — push to a repo and enable Pages

No build tools or server-side code required.

## License

© Lona Smith. All rights reserved.
