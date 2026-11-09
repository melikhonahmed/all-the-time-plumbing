# All The Time Plumbing

This repository contains the custom-coded website and design system for **All The Time Plumbing** (Houston Master Plumber, License #41889).

---

## 🚀 Live Local Preview

To launch the local preview server:

```bash
npm start
# or:
npx serve -l 3000 .
```

Then visit:
- **Active Website (`index.html`):** [http://localhost:3000](http://localhost:3000)

---

## 📁 Project Structure

```
all the time plumbing/
├── index.html                   # Primary active landing page
├── DESIGN.md                    # Brand design system specification (tokens, typography, elevation, spacing)
├── design-system.json           # Raw design tokens and project styling metadata
├── site-manifest.json           # Project manifest and asset metadata
├── package.json                 # Project configuration and preview scripts
├── images/                      # Locally downloaded high-resolution assets & brand logos
│   ├── logo.png                 # Brand logo
│   ├── hero-infrastructure.jpg  # Hero pipe infrastructure photo
│   ├── tom-moreno.jpg           # Master Plumber Tom Moreno photo
│   ├── plumbing-repairs.jpg     # Plumbing service technician
│   ├── water-heater.jpg         # Water heater installation
│   ├── water-filtration.jpg     # Water filtration systems
│   ├── leak-detection.jpg       # Slab and hidden leak detection
│   ├── customer-guarantee.jpg   # Happy Houston homeowner
│   └── video-spotlight.jpg      # Video spotlight thumbnail
└── assets/                      # Supporting site assets and custom UI files
```

---

## 🎨 Design System: Reliable Industrial Precision

- **Primary Brand Red:** `#E53924` (Urgent, high-trust emergency actions)
- **Deep Charcoal:** `#14171A` / `#1A1D20` (Architectural ground & contrast)
- **Warm Cream Background:** `#FAF8F5` (Clean, sanitary residential comfort)
- **Cream Card Surface:** `#F4F0E8` / `#FFFFFF`
- **Typography:**
  - Headlines & CTAs: `Plus Jakarta Sans` (Weights 700 to 900)
  - Body & Microcopy: `Inter` (Weights 400 to 600)
- **Shapes & Elevation:**
  - Signature Arched Radii: `160px 160px 24px 24px`
  - Base Card Radius: `8px` (`0.5rem`)
  - Status Badges: Pill (`9999px`)
- **Key Features:**
  - 24/7 Live Emergency Dispatch sticky indicator
  - Tap-to-call direct dial `(713) 705-3926`
  - Interactive "Book Online" service estimate modal
  - Responsive mobile navigation drawer with hamburger toggle
  - Complete zero-latency offline imagery

