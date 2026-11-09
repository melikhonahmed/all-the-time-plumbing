## Brand & Style

This design system is tailored for high-urgency, trust-critical trade services. The brand persona blends master craftsmanship with modern efficiency: authoritative, responsive, fair, and relentlessly dependable. 

Targeting residential homeowners, property managers, and commercial operators in moments of stress (such as burst pipes or emergency water heater failures), the user interface prioritizes clarity, immediate call-to-actions, and certified trust signals. Visuals follow a high-contrast corporate modern style paired with subtle industrial precision: razor-sharp hierarchy, bold utilitarian headlines, high-visibility emergency dispatch badges, and crisp card surfaces that eliminate visual clutter in high-conversion decision moments.

## Layout & Spacing

A 12-column responsive layout anchors large display screens and desktops, stepping down gracefully to 8 columns on tablets and 4 columns on mobile handsets.

- **Breakpoints**: 
  - Mobile: `< 640px` (Margins: `1rem`, Gutter: `1rem`)
  - Tablet: `640px – 1024px` (Margins: `2rem`, Gutter: `1.5rem`)
  - Desktop: `> 1024px` (Max container width: `1280px`, Section margins: `2.5rem` to `4rem`)
- **Rhythm Philosophy**: Dense enough to keep contact points and service breakdowns above the fold on mobile, yet generously spaced across desktop sections to present enterprise-grade trustworthiness. Key emergency telephone bars sit pinned or prominently top-stacked with zero clutter.

## Elevation & Depth

Visual hierarchy uses crisp, low-contrast structural borders alongside low-opacity ambient shadows. The interface avoids artificial skeumorphic bevels and heavy drops in favor of architectural, clinical cleanliness:

- **Level 0 (Flat Ground)**: `#FFFFFF` or `#F8FAFC`. Zero elevation, delimited by 1px solid `#E2E8F0` borders.
- **Level 1 (Cards & Service Grids)**: Crisp background with a subtle ambient shadow: `0 1px 3px 0 rgba(24, 24, 27, 0.05), 0 1px 2px -1px rgba(24, 24, 27, 0.05)` coupled with a 1px border of `#E2E8F0`.
- **Level 2 (Dropdowns & Floating Booking Bar)**: Pinned CTA headers and interactive overlays utilize `0 10px 15px -3px rgba(24, 24, 27, 0.08), 0 4px 6px -4px rgba(24, 24, 27, 0.04)`.
- **Level 3 (Emergency Modals & Dispatch Dialogues)**: High focus depth: `0 20px 25px -5px rgba(24, 24, 27, 0.15), 0 8px 10px -6px rgba(24, 24, 27, 0.1)`.

## Components

### Buttons & CTAs
- **Primary Emergency CTA**: High-contrast `#E53924` surface with `#FFFFFF` bold text. Includes subtle hover shift to `#C92A17` and an active press depth of `transform: scale(0.98)`. Emphasizes direct telephone triggers with integrated icon affordances.
- **Secondary Charcoal Action**: `#18181B` surface with `#FFFFFF` text for non-emergency scheduling, financing calculators, and portfolio browsing.
- **Tertiary Ghost Outline**: 1.5px solid `#E2E8F0` border with `#18181B` text, shifting to `#F1F5F9` on hover.

### Service Cards
- Pure white container with a 1px `#E2E8F0` border and `8px` corner radius. Cards feature a top image container with uniform aspect ratio (`16:10`), followed by a `1.25rem` padded content block including headline, brief scope, and a full-width bottom CTA button.

### Badges & Chips
- **Emergency 24/7 Chip**: Soft tinted red background (`rgba(229, 57, 36, 0.1)`) with `#E53924` text and a pulsing live status dot.
- **Trust Badges**: White pills with a 1px border of `#E2E8F0`, containing verified license numbers (e.g., "MPL: 41889") or Google Review star ratings in rich golden amber (`#F59E0B`).

### Form Inputs
- 48px height with a 1px `#CBD5E1` border on `#FFFFFF` base. Focused inputs transition to a 2px outer ring in primary red (`rgba(229, 57, 36, 0.2)`) and a `#E53924` border. Includes bold labels and clear helper copy for quick problem descriptions.

### Trust & Credibility Banners
- Dedicated horizontal strips for partner certifications (Rheem, Lochinvar, PHCC, HomeAdvisor) displayed in grayscale with hover-to-color transition, reinforcing neighborhood longevity and master plumber status.