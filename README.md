# FishLog Website

Landing page for the FishLog iOS app - Your AI-Powered Fishing Companion.

## Tech Stack

- **Framework**: [Astro](https://astro.build/) - Static site generator
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS
- **Hosting**: Netlify / Vercel (configured for both)

## Getting Started

### Prerequisites

- Node.js 20+
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
src/
├── components/     # Astro components
│   ├── Header.astro
│   ├── Hero.astro
│   ├── Features.astro
│   ├── HowItWorks.astro
│   ├── Testimonials.astro
│   ├── Pricing.astro
│   ├── EmailSignup.astro
│   ├── Download.astro
│   └── Footer.astro
├── layouts/        # Page layouts
│   └── Layout.astro
├── pages/          # Route pages
│   ├── index.astro
│   ├── privacy.astro
│   └── terms.astro
└── styles/         # Global styles
    └── global.css

public/             # Static assets
├── images/
├── robots.txt
└── site.webmanifest
```

## Deployment

### Netlify

1. Connect repository to Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`

### Vercel

1. Import project to Vercel
2. Framework preset: Astro
3. Deploy

## Features

- Responsive design for all devices
- Optimized for performance (static generation)
- SEO-ready with Open Graph and Twitter cards
- Email signup for Android waitlist
- Pricing section with App Store integration

## License

© 2025 FishLog. All rights reserved.
