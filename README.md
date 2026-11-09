# All The Time Plumbing

A responsive website for All The Time Plumbing, a residential and commercial plumbing company serving Houston, Texas. The site highlights plumbing services, the company’s master plumber, customer reviews, and ways to request service.

**Business:** All The Time Plumbing · Houston, TX

**Phone:** [(713) 705-3926](tel:7137053926)

**License:** Texas State Master Plumber MPL #41889

## Website features

- Responsive layouts for desktop, tablet, and mobile
- Service listings and company information
- Tap-to-call phone links and a mobile emergency call button
- Mobile navigation menu
- Service request modal
- Customer testimonials and social links
- Locally stored images and a logo favicon

## Preview locally

### Requirements

- Node.js and npm

### Start the preview server

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser. The `dev` script starts the same local preview server:

```bash
npm run dev
```

## Deploy to Vercel

This is a static website and does not require a Vercel-specific package or build step. The included `vercel.json` tells Vercel to serve the project root directly without installing dependencies.

To deploy from GitHub:

1. Import the repository in Vercel.
2. Keep the project root set to `.` and the framework preset set to **Other**.
3. Deploy. Vercel will serve `index.html` and the files in `images/`.

## Project structure

```text
.
├── index.html           # Website and page styles/scripts
├── images/              # Website photos and logos
├── vercel.json          # Vercel static deployment settings
├── DESIGN.md            # Brand and visual design guidelines
├── design-system.json   # Design tokens and project styling metadata
├── image_mapping.json   # Image asset mappings
├── site-manifest.json   # Site and design manifest
└── package.json         # Project metadata and preview scripts
```

## Design

The visual system pairs a warm, light background with charcoal surfaces and a red accent:

| Token | Color |
| --- | --- |
| Brand red | `#E53924` |
| Deep charcoal | `#14171A` |
| Warm cream | `#FAF8F5` |

The page uses Plus Jakarta Sans, Tailwind CSS via its CDN, and locally stored image assets. Google Fonts are used for typography.

## Notes

This repository contains the website source. The booking form currently demonstrates a front-end request flow; connect it to a service or backend to receive and process submissions.
