# Project Overview: Advet Buildwell

Advet Buildwell is a high-fidelity, minimalist real estate platform designed to prioritize architectural stewardship and human-centric living spaces. The project emphasizes clean typography, localized assets, and a "museum-style" design aesthetic.

## 🛠 Technology Stack

- **Core**: Semantic HTML5 & JavaScript.
- **Styling**: Tailwind CSS (Local distribution `assets/js/tailwind.min.js`).
- **Typography**: Custom font system featuring `DM Sans` (Sans) and `Cormorant Garamond` (Serif).
- **Assets**: fully localized images and icons (SVG) stored in `assets/images/`.
- **Interactions**: Custom CSS animations (`reveal`, `image-soft-clip`) and high-end hover effects.

## 📂 Page Architecture

The platform consists of **17 core pages** categorized into Public, Search, and Administration layers.

### Public Facing Pages
1.  **Index**: Hero-led introduction to the brand with primary project showcases.
2.  **About Us**: Contextual narrative about the studio's history and architectural legacy.
3.  **Philosophy**: Deep dive into the studio's "Sanctuary-first" approach to real estate.
4.  **Listings**: Main property search and filter interface.
5.  **Spaces**: An atmospheric gallery of "Space Archetypes" and curated collections.
6.  **Stories**: A journal/blog layer for architectural insights and fieldwork.
7.  **Contact**: Minimalist inquiry form and studio location details.
8.  **Property Detail**: Immersive, high-stakes view of individual assets (e.g., The Obsidian Villa).
9.  **Changelog**: Transparency log for project updates (currently v1.1.0).

### Authentication
10. **Login**: Secure gateway for members and partners.
11. **Register**: Account creation for localized dashboards.

### Admin Dashboard Layer
12. **Admin Dashboard**: Centralized metric overview and system status.
13. **Listings Management**: CRUD interface for managing property inventory.
14. **Add Property**: Dedicated onboarding form for new real estate assets.
15. **Inquiry Manager**: Communication hub for tracking client leads.
16. **Market Analytics**: Detailed examination of spatial demand, demographics, and portfolio frequency (Chart.js integration).
17. **Studio Settings**: Configuration for branding tokens, architectural frequency, access governance, and communication rhythm.

---

## ✨ Key Features

### 🖼 High-Fidelity Design System
- **Museum Aesthetic**: Purposeful use of white space to isolate high-end imagery.
- **Glassmorphism**: Subtle use of backdrop blurs and translucent surface colors (`bg-background/80`).
- **Localized Assets**: Zero reliance on external CDNs or brittle image links; everything is optimized and stored locally.

### 🏠 Property Experience
- **Atmosphere Metrics**: Detailed breakdown of "Primary Volumes" and "Sensory Design" (e.g., Acoustic Stillness) in property views.
- **Material Palettes**: Transparent listing of raw building materials (Travertine, Basalt, Oak).
- **Interactive Galleries**: 10-second subtle zoom animations and soft-clip corners on all primary visuals.

### 📨 Functional Modules
- **Newsletter Feature**: Integrated newsletter signup in the global footer with validated email capture.
- **Global Navigation**: Unified menu across all pages including a persistent "Home" link.
- **Responsive Layouts**: Breakpoint-specific logic to prevent overlapping on mobile (re-engineered sticky headers and aspect ratios).

### ⚙️ System Integrity & Operations
- **Analytics**: Beautifully styled Chart.js integrations for market valuation and buyer demographic intelligence.
- **Global Settings**: Robust configuration portal for MFA security, newsletter rhythm, and dynamic branding tokens.
- **Version Tracking**: Structured changelog system documenting phases like "Asset Localization" and "The Refinement Phase."
- **Internal Interlinking**: Fully functional internal routing between all 17 pages.

---

## 🎨 Design Tokens

- **Palette**: Neutral background (`#FDFCF9`), deep foreground (`#2A2925`), and natural accent (`#899178`).
- **Typography**: Serif for narrative headers (Cormorant Garamond) and Sans for technical data (DM Sans).
- **Corner Style**: Uniform `2.5rem` soft-clip radius for all significant architectural visuals.
