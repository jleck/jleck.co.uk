# CLAUDE.md

## Project Overview

Personal portfolio website for jleck.co.uk. A single-page static site with a hero section, freelance hire banner, and experience timeline.

## Structure

- `index.html` — Single page with all content (hero, hire banner, experience timeline, footer)
- `global.css` — All styles using CSS custom properties
- `favicon.svg` / `favicon.ico` — Site icons
- `CNAME` — GitHub Pages custom domain (`www.jleck.co.uk`)
- `robots.txt` — Search engine crawling rules
- `.editorconfig` — Editor formatting rules (2-space indent, UTF-8, LF line endings)

## Conventions

- No build step — plain HTML and CSS
- CSS uses custom properties defined in `:root` for theming
- Font stack: Inter (sans) and JetBrains Mono (mono) via Google Fonts
- Dark theme by default
- BEM-like class naming (e.g., `.hero-wrapper`, `.timeline-item`, `.hire-content`)
- Mobile-first responsive with a 640px breakpoint
