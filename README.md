# Library Digital Focus Screen

A serene, single-file HTML application designed for library study spaces. Features a warm, literary aesthetic with a live clock, rotating motivational quotes, customizable timer/stopwatch, and gentle ambient particle animation.

## ✨ Features

- **Live Clock & Date** — 12-hour format with real-time updates
- **Rotating Quotes** — 28 study-focused lines rotating every 10 minutes (synchronized across all instances)
- **Timer & Stopwatch** — Presets (15, 25, 60, 120 min) + custom duration input
- **Dim/Focus Mode** — Toggle for a quieter screensaver aesthetic
- **Ambient Motes** — Drifting particle animation (respects `prefers-reduced-motion`)
- **Responsive Design** — Adapts beautifully from desktop to mobile
- **No Dependencies** — Pure HTML/CSS/JavaScript + Google Fonts

## 🎨 Design

- **Color Palette**
  - Deep Indigo (`#0c1220`) — main background
  - Brass Gold (`#c9a35e`) — accent, progress indicators
  - Sage Teal (`#6f9c8f`) — timer numbers
  - Paper (`#f5f5f5`) — text

- **Typography**
  - **Fraunces** (serif) — clock, quotes, timer (literary warmth)
  - **Work Sans** (sans) — labels, buttons, dates (clarity)

## 🚀 Deployment

This project is deployed on Vercel.

### Deploy Your Own

1. Fork or clone this repository
2. Push to GitHub
3. Visit [Vercel](https://vercel.com) and connect your GitHub account
4. Select this repository and click **Deploy**
5. Your site will be live in seconds!

Alternatively, use the Vercel CLI:

```bash
npm i -g vercel
vercel
```

## 📝 Files

- **library-focus-screen.html** — Main application (structure, styles, logic in one file)
- **vercel.json** — Vercel deployment configuration
- **README.md** — This file

## 🛠️ Customization

All design tokens are defined in the `:root` CSS variables. Edit these to customize colors:

```css
:root {
  --bg-deep: #0c1220;      /* Main background */
  --glow: #c9a35e;         /* Accent color */
  --sage: #6f9c8f;         /* Timer color */
  --paper: #f5f5f5;        /* Text color */
  /* ... */
}
```

## 📱 Browser Support

- Chrome, Firefox, Safari, Edge (modern versions)
- Mobile browsers (iOS Safari, Chrome Mobile, Firefox Mobile)
- Respects `prefers-reduced-motion` for accessibility

## 📄 License

Open source. Feel free to use and modify for your library or study space.
