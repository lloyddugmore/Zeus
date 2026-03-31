# Zeus Property Management

A professional property management marketing website built with [Astro](https://astro.build). Zeus Property Management offers full-service residential property management across New Zealand.

## Pages

| Route | Description |
|---|---|
| `/` | Home — hero, services preview, why Zeus, testimonials |
| `/services` | Full breakdown of all six services |
| `/about` | Company story, values, and team |
| `/contact` | Contact form and office details |

## Tech Stack

- **Framework** — [Astro 4](https://astro.build)
- **Styling** — Scoped CSS + global CSS custom properties
- **Fonts** — Inter (body) & Playfair Display (headings) via Google Fonts
- **Icons** — Inline SVG

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Install dependencies

```bash
npm install
```

### Development server

```bash
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

### Build for production

```bash
npm run build
```

Output is written to `dist/`.

### Preview production build

```bash
npm run preview
```

## Project Structure

```
Zeus/
├── public/               # Static assets (favicon, etc.)
├── src/
│   ├── components/
│   │   ├── Header.astro  # Fixed navigation header
│   │   └── Footer.astro  # Site footer with links & contact info
│   ├── layouts/
│   │   └── Layout.astro  # Base HTML layout & global styles
│   └── pages/
│       ├── index.astro   # Home page
│       ├── services.astro
│       ├── about.astro
│       └── contact.astro
└── package.json
```

## Design Tokens

Global CSS variables are defined in `src/layouts/Layout.astro`:

| Variable | Value | Usage |
|---|---|---|
| `--navy` | `#0d1b2a` | Primary dark background |
| `--navy-light` | `#1b2d42` | Secondary dark background |
| `--gold` | `#c9a84c` | Accent / brand colour |
| `--gold-light` | `#e5c97e` | Hover states |
| `--white` | `#ffffff` | Primary background |
| `--off-white` | `#f8f7f4` | Alternate section background |
| `--text` | `#2c2c2c` | Body text |
| `--text-muted` | `#6b7280` | Secondary text |
