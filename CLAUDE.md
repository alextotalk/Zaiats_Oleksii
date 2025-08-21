# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static resume/portfolio website for Oleksii Zaiats, a Golang/Full Stack Developer. The site is built with pure HTML, CSS, and uses Font Awesome for icons.

## Project Structure

```
/
├── index.html          # Main resume page
├── styles.css          # All styling and responsive design
├── CV_Alex_Zayets_En.pdf # PDF version of resume
├── favicon-gopher.png  # Go gopher favicon
├── 1234.png           # Image asset
└── CLAUDE.md          # This file
```

## Development Commands

This is a static website with no build process required. To develop:

1. **Local development**: Open `index.html` directly in a browser or use a simple HTTP server:
   ```bash
   python3 -m http.server 8000
   # or
   npx serve .
   ```

2. **Live reloading** (if needed): Use any static file server with live reload capability

## Architecture Overview

**Static HTML Resume Site**:
- Pure HTML/CSS implementation with no JavaScript
- Responsive design with mobile-first approach
- Font Awesome icons via CDN for visual elements
- Go gopher favicon reflecting the developer's specialization
- Print-optimized styles for PDF generation

**Key Design Patterns**:
- CSS Grid and Flexbox for responsive layouts
- CSS custom properties could be added for theming
- Semantic HTML structure for accessibility
- Mobile-responsive breakpoints at 768px

## Styling Architecture

**CSS Organization** (`styles.css`):
- Global reset and base styles
- Component-based sections (header, main-content, etc.)
- Responsive design with media queries
- Print styles for PDF generation
- Hover effects and transitions for interactivity

**Color Scheme**:
- Primary: `#2c3e50` (dark blue)
- Accent: `#3498db` (light blue)
- Background: `#f4f4f4` (light gray)

## Content Structure

The resume includes:
- Personal header with contact information
- Professional summary
- Work experience with detailed responsibilities
- Technical skills organized by category
- Languages proficiency
- Education background

## Deployment

This static site can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply upload the files to the hosting provider's root directory.