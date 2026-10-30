# Nethra Shree — Personal Portfolio Website

An elegant, minimal, and modern personal portfolio website for **Nethra Shree**, an aspiring Artificial Intelligence & Machine Learning engineer pursuing B.Tech at SRM Institute of Science and Technology, Ramapuram, Chennai (2026–2030).

## Design System & Colour Palette

| Element | Color Hex | Color Name | Role |
| :--- | :--- | :--- | :--- |
| **Background** | `#FCF9EA` | Warm Cream | Dominant backdrop for clean, editorial breathing room |
| **Hero Heading** | `#DB9558` | Muted Caramel | Distinctive display typography |
| **Main Content** | `#A8BBA3` | Sage Green | Content styling, subtle fills, tags, and highlights |
| **Borders & Outlines** | `#97A87A` | Olive Green | Structural 1px dividers, grid outlines, and frames |

### Typography
- **Headings & Display**: `EB Garamond` (Google Font)
- **Body & Paragraphs**: `Source Serif 4` (Google Font)
- **Labels, Dates & Metadata**: `IBM Plex Mono` (Google Font)

## Features & Editorial Architecture

- **Editorial Heading Rail**: Desktop layout features a structured left rail with section indexing and title, aligning main content along a unified vertical guide.
- **Strict Square Corners**: No rounded borders (`border-radius: 0px`) echoing Swiss/editorial minimalism.
- **100% Genuine Information**: Accurate academic profile without fabricated metrics or fake progress bars.
- **Modern Web Standards**:
  - Accessible form validation using `:user-valid` and `:user-invalid` pseudo-classes (error messages deferred until user interaction).
  - Screen reader synchronization with `aria-invalid` and `aria-errormessage`.
  - Real email compose handling targeting `nebula8002@gmail.com` with formatted drafts and one-click clipboard copying.
  - Reduced-motion accessibility (`prefers-reduced-motion: reduce`).
  - WCAG-compliant contrast ratios.

## Quick Start / Local Preview

1. **Option 1: Direct Open**
   Open `index.html` directly in any web browser.

2. **Option 2: Node.js Local Server**
   ```bash
   node server.js
   # or
   npm start
   ```
   Navigate to `http://localhost:3000`.

## Deployment

The project has zero complex dependencies and can be deployed directly to:
- **GitHub Pages**: Push to repository and enable GitHub Pages on `main` branch.
- **Vercel / Netlify**: Deploy as a static site pointing to the root directory.

---
&copy; 2026 Nethra Shree. All rights reserved.

