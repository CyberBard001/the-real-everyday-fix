# The Real Everyday Fix

A Hugo-based health reset website, designed for mobile and desktop, with Netlify and GitHub deployment.

## Features
- 4-week plan with daily habits, exercise, meal, and physio tracking
- Reusable shortcodes: meal-logger, daily-tracker, physio-tracker (all use localStorage)
- Static pages for meals and stretches
- Responsive hero banner
- Minimal custom CSS for a clean, mobile-friendly look

## Local Development
1. Install [Hugo Extended](https://gohugo.io/getting-started/installing/).
2. Clone this repo:
   ```powershell
   git clone https://github.com/CyberBard001/the-real-everyday-fix.git
   cd the-real-everyday-fix
   git submodule update --init --recursive
   ```
3. Start the server:
   ```powershell
   hugo server
   ```
4. Visit [http://localhost:1313](http://localhost:1313)

## Deployment
- Push to GitHub triggers Netlify build.
- Netlify uses `hugo` as build command, `public` as publish dir, and latest extended Hugo version.

## Tech Used
- [Hugo](https://gohugo.io/)
- [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod)
- [Netlify](https://www.netlify.com/)
- [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) for persistence

---
MIT License
