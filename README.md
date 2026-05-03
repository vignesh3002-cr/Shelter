# Shelter Group — Analytics Platform

React 18 + Tailwind CSS 3 · 3-page project tracker

## Pages
1. **Login** — Sign in → navigates to Project Master
2. **Project Master** — List of projects with search/filter → "View Report" navigates to Report
3. **Activity Report** — Grouped bar chart (Y: Activities, X: Codes A–E) + score table

## Local dev
```bash
npm install
npm run dev        # http://localhost:5173
```

## Deploy (Netlify / Vercel / any static host)
```bash
npm run build      # outputs to /dist
```
Upload the `/dist` folder — that's it.

### Netlify (drag & drop)
1. Run `npm run build`
2. Go to netlify.com → "Add new site" → "Deploy manually"
3. Drag the `/dist` folder into the drop zone

### Vercel (CLI)
```bash
npm i -g vercel
vercel --prod
```

### GitHub Pages
Push repo, set Pages source to `dist/` branch or use the `gh-pages` npm package.

## Tech stack
- React 18
- Tailwind CSS 3
- Vite 4
- Fonts: Sora + JetBrains Mono (Google Fonts)
