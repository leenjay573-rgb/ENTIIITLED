# flamel3ss — Terminal Portfolio

A single-page, terminal-inspired portfolio for "flamel3ss" (Takeshi Souma).

## Features
- Loader screen with progress bar (skippable with Space/Enter or click)
- Terminal grid layout: main content and sidebar
- Deep red, gold, and silver color scheme
- Animated scanlines, flicker, and glitch effects
- Primary project box pulses twice after 2 seconds on load
- Fully responsive and mobile-friendly
- Accessible: keyboard navigation, ARIA roles, focus management
- Optimized for performance and cross-system compatibility

## How to run locally

```powershell
cd 'c:\Users\Destr\OneDrive\Desktop\Echo\about-me'
python -m http.server 5500  # then open http://localhost:5500
```

## Customization
- Edit `index.html` for content, projects, and sidebar
- Adjust color variables and animation in the `<style>` block
- Replace the hero image with your own (update the `img` src)

## Deployment
- Static site: can be deployed to GitHub Pages, Netlify, Vercel, or any static host
- For GitHub Pages: copy all files to your repo and enable Pages in repo settings

## Accessibility & Performance
- Respects `prefers-reduced-motion` for users who disable animations
- Uses Google Fonts (`Inconsolata`) for improved monospace rendering
- ARIA roles and keyboard focus for loader and main content

---

For further enhancements (SEO, PWA, analytics, or more animations), open an issue or request a feature!
