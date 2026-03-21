# Steve De Vera — Portfolio

Personal portfolio built with [Astro](https://astro.build), deployed on GitHub Pages.

## Tech Stack
- **Framework**: Astro 4
- **Styling**: Pure CSS with custom design system
- **Fonts**: Syne (display) + DM Sans (body)
- **Deployment**: GitHub Pages via GitHub Actions

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview build
npm run preview
```

## Deploying to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **GitHub Actions**
4. Push to `main` — it auto-deploys!

Your site will be live at: `https://synxdvr.github.io`

## Customization Checklist

- [ ] Update `astro.config.mjs` with your GitHub username
- [ ] Replace all `yourusername` links with real GitHub/LinkedIn URLs
- [ ] Update email in Contact section
- [ ] Add real GitHub repo links for each project
- [ ] Add your photo (replace avatar placeholder in About.astro)
- [ ] Add `cv.pdf` to the `/public` folder
- [ ] Update the favicon in `/public/favicon.svg`

## Structure

```
src/
├── components/
│   ├── Nav.astro          # Sticky navigation
│   ├── Hero.astro         # Landing section with code card
│   ├── About.astro        # Bio and quick facts
│   ├── Skills.astro       # Tech stack + proficiency bars
│   ├── Projects.astro     # All 5 projects
│   ├── Experience.astro   # Work + education timeline
│   └── Contact.astro      # Contact form + footer
├── layouts/
│   └── Layout.astro       # Base HTML layout
├── pages/
│   └── index.astro        # Main page
└── styles/
    └── global.css         # Design system + global styles
```
