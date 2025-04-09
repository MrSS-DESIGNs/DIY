# DIY Club Website

Welcome to the DIY Club Website project! This repository contains an interactive website showcasing events, gallery, and inspiration zone. Built with HTML, CSS, JavaScript, and Bootstrap, it offers a modern user experience.

## Project Overview

This project includes:
- **Event.html**: Features upcoming and past events with interactive elements.
- **Gallery.html**: Showcases club projects with filters and lightbox functionality.
- (Optional: Add more pages like Index.html if available)

This README details all features, setup instructions, and future enhancements.

---

## Features

### General Features
- **Responsive Design**: Fully responsive layout using Bootstrap 4.5.2.
- **Dark Mode Toggle**: Switch between light and dark themes via navbar button.
- **Smooth Scrolling**: Smooth navigation to sections using anchor links.
- **Scroll Reveal**: Animations for sections as they enter the viewport.

### Custom Cursor
- **Default Cursor**: Custom crosshair (`+`) cursor style across the page.
  - Defined using SVG: `<svg><path d="M10 4V16M4 10H16" stroke="#FF6F61"/></svg>`.
- **Hover Cursor**: Ring effect (`<circle cx="15" cy="15" r="12" stroke="#FFD54F"/>`) on interactive elements (links, buttons, cards).
- **Implementation**: Set via CSS `cursor` property with data URLs.

### Progress Bar
- **Visual Indicator**: Fixed top bar showing scroll progress.
- **Dynamic Update**: Width adjusts based on scroll position (0% to 100%).
- **Styling**: Colored in `#FF6F61` with smooth transition.
- **Behavior**: Updates in real-time as user scrolls.

### Preloader
- **Loading Animation**: Full-screen spinner displayed during page load.
- **Icon**: Font Awesome spinning icon in `#FF6F61`.
- **Fade Out**: Transitions to opacity 0 and removes after 0.5s.
- **Z-Index**: Set to 9999 for overlay effect.

### Social Media Bar
- **Fixed Position**: Stays on the left side, centered vertically.
- **Links**: Includes Twitter, Instagram, and LinkedIn with hover effects.
- **Hover Tooltip**: Displays URL on hover with a colored background.
- **Styling**: Semi-transparent background with shadow, scales on hover.

### Event.html Specific Features
- **Parallax Hero Section**: Fixed background image with dark overlay.
- **Countdown Timer**: Real-time countdown to May 1, 2025 event.
- **Event Cards**: Hover zoom and modal popups for details.
- **Modal Popups**: Detailed event info on click.
- **Past Events Carousel**: Auto-sliding with hover zoom.
- **CTA Banner**: Fixed "Join Now" banner with fade effect.
- **Sticky Navbar Shrink**: Shrinks on scroll for better visibility.

### Gallery.html Specific Features
- **Hero Section**: Background image with overlay.
- **Best Projects Section**: Featured projects with zoom and badges.
- **Full Gallery with Tabs**: Categories (All, Woodworking, Electronics, Crafts).
- **Gallery Search Filter**: Dynamic search bar to filter projects.
- **Lightbox Modal**: Zoom-in/out functionality for images.
- **Inspiration Zone**: Cards with hover glow and parallax background.
- **Vanilla Tilt Effect**: 3D tilt on gallery and best project items.

### Footer
- **Fixed Content**: Centered copyright text at the bottom.
- **Dynamic Year**: Updates automatically to current year (e.g., © 2025).
- **Dark Mode Support**: Dark background (`#333`) in light mode, darker (`#111`) in dark mode.
- **Styling**: Simple padding and text alignment.

---

 
