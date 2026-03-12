# Advet Buildwell – Real Estate Website

A modern **luxury real estate website interface** designed for showcasing premium properties, brand storytelling, and portfolio management.
The project provides a **beautiful public website** for visitors and a **private admin dashboard** for managing listings and inquiries.

The design focuses on **minimalist architecture, elegant typography, and smooth user experience** using **TailwindCSS and modern frontend practices**.

---

# Preview

This project represents the digital presence of **Advet Buildwell**, a fictional luxury real-estate studio focused on curated architectural spaces.

Key design concepts:

* Earth-tone color palette (Sage, Sand, Bone)
* Serif + Sans typography pairing
* Soft reveal animations
* Minimalist UI
* Responsive layouts

---

# Features

## Public Website

The public interface allows visitors to explore the brand, properties, and stories.

### Pages Included

* **Home** – Landing page introducing the brand
* **About Us** – Company background and vision
* **Philosophy** – Design philosophy and values
* **Listings** – Property discovery and browsing
* **Spaces** – Gallery of curated properties
* **Stories** – Editorial and storytelling content
* **Property Details** – Detailed property showcase
* **Contact** – Client inquiries
* **Login / Register** – User authentication pages
* **Changelog** – Development progress documentation

### Property Experience

Users can:

* Browse available properties
* View image galleries
* Explore property descriptions
* Learn about neighborhoods
* Contact the studio for inquiries

---

# Admin Dashboard

The project also includes a **private admin portal** for managing the real-estate portfolio.

### Admin Features

Admin users can:

* Access a **central dashboard**
* Manage property listings
* Add new properties
* Monitor client inquiries
* View property portfolio data

### Admin Pages

* `admin-dashboard.html`
* `admin-listings.html`
* `add-property.html`
* `admin-inquiries.html`

---

# Tech Stack

Frontend technologies used in this project:

* **HTML5**
* **TailwindCSS**
* **JavaScript**
* **Google Fonts**

Fonts used:

* **DM Sans**
* **Cormorant Garamond**

---

# UI Design System

### Color Palette

| Color      | Purpose |
| ---------- | ------- |
| Background | #FDFCF9 |
| Foreground | #2A2925 |
| Muted      | #6D685C |
| Surface    | #F4F0E6 |
| Accent     | #899178 |
| Sand       | #DFD8CC |

The palette reflects **natural architectural tones** inspired by stone, sand, and organic materials.

---

# Project Structure

```
project-root
│
├── index.html
├── about.html
├── philosophy.html
├── listings.html
├── spaces.html
├── stories.html
├── property-detail.html
├── contact.html
├── login.html
├── register.html
├── changelog.html
│
├── admin-dashboard.html
├── admin-listings.html
├── add-property.html
├── admin-inquiries.html
│
└── assets
    ├── images
    ├── icons
    └── styles
```

---

# UI Features

### Smooth Reveal Animations

The project uses **CSS keyframe animations** for soft content appearance.

Example:

```css
.reveal {
 opacity: 0;
 transform: translateY(20px);
 animation: soft-reveal 1s ease forwards;
}
```

---

### Responsive Layout

The layout is optimized for:

* Mobile
* Tablet
* Desktop

Using Tailwind's responsive utilities.

---

# Navigation System

A **unified navigation bar** is implemented across all pages with:

* Backdrop blur effect
* Consistent spacing
* Smooth transitions

---

# Forms

Forms are standardized across:

* Login
* Register
* Contact
* Admin tools

Ensuring consistent UX.

---

# Version

### v1.0.0 – Initial Release (March 12, 2026)

Initial launch includes:

* Full website architecture
* Property listing system
* Admin management portal
* Responsive UI system
* Design identity framework

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/advet-buildwell.git
```

Open the project folder and launch any HTML file in your browser:

```bash
index.html
```

No build tools are required.

---

# Future Improvements

Planned enhancements:

* Backend integration
* Property database
* User authentication system
* CMS for property management
* Image optimization
* SEO improvements
* API-based property search

---

# License

This project is open-source and available under the **MIT License**.

---

# Author

Developed as a **frontend architecture project for luxury real estate platforms**.
