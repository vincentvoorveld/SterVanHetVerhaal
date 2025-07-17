# Ster van het Verhaal - Gepersonaliseerde Kinderboeken

## Overview

This repository contains a landing page for "Ster van het Verhaal" (Star of the Story), a Dutch service that creates personalized children's books. The project is a single-page application built with vanilla HTML, CSS, and JavaScript, utilizing Tailwind CSS for styling and Font Awesome for icons.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static Website**: Simple HTML-based landing page with no backend dependencies
- **Styling Framework**: Tailwind CSS loaded via CDN for rapid UI development
- **JavaScript**: Vanilla JavaScript for basic interactivity (navigation, smooth scrolling)
- **Responsive Design**: Mobile-first approach with responsive navigation and layout

### Technology Stack
- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Utility-first CSS framework loaded from CDN
- **Font Awesome**: Icon library for visual elements
- **Custom CSS**: Minimal custom styling for smooth scroll behavior

## Key Components

### 1. Navigation System
- **Fixed Navigation**: Sticky header with backdrop blur effect
- **Responsive Menu**: Hidden mobile menu (hamburger icon visible on mobile)
- **Smooth Scrolling**: CSS-based smooth scroll behavior for anchor links
- **Navigation Sections**: Home, Aanbod, Voorbeelden, Over Mij, Wachtlijst, FAQ

### 2. Color Scheme
- **Custom Tailwind Colors**: Extended color palette with warm, child-friendly colors
  - Warm Yellow (#FEF3C7)
  - Soft Pink (#FCE7F3)
  - Light Blue (#DBEAFE)
  - Mint Green (#D1FAE5)
  - Lavender (#EDE9FE)
  - Peach (#FED7AA)

### 3. Visual Design
- **Gradient Background**: Warm yellow to soft pink gradient
- **Glass-morphism**: Navigation uses backdrop blur with transparency
- **Icon Integration**: Star icon in navigation representing the brand

## Data Flow

### Static Content Flow
1. **HTML Structure**: Single-page layout with semantic sections
2. **CSS Styling**: Tailwind classes applied directly to HTML elements
3. **JavaScript Enhancement**: Minimal JavaScript for user interactions
4. **CDN Resources**: External resources loaded from CDNs (Tailwind, Font Awesome)

### Navigation Flow
- Hash-based navigation using anchor links
- Smooth scrolling between sections
- Responsive menu toggle for mobile devices

## External Dependencies

### CDN Dependencies
- **Tailwind CSS**: `https://cdn.tailwindcss.com`
- **Font Awesome**: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css`

### No Backend Dependencies
- Static hosting compatible (no server-side processing required)
- No database connections
- No API integrations currently implemented

## Deployment Strategy

### Static Hosting
- **Deployment Type**: Static website hosting
- **Compatible Platforms**: GitHub Pages, Netlify, Vercel, traditional web servers
- **Build Process**: No build step required (direct HTML/CSS/JS)
- **Performance**: Fast loading with CDN-based resources

### Optimization Considerations
- **CDN Usage**: External resources loaded from CDNs for faster delivery
- **Minimal JavaScript**: Lightweight approach with vanilla JS
- **Responsive Design**: Mobile-optimized for various screen sizes
- **SEO Ready**: Semantic HTML structure with proper meta tags

## Recent Changes

### January 2025 Updates
- **Wachtlijst System**: Replaced ordering section with waiting list concept
- **FAQ Section**: Added interactive collapsible FAQ section with detailed answers
- **Content Updates**: Removed page count specification from full book offering
- **Navigation**: Updated navigation menu to include Wachtlijst and FAQ sections
- **Book Examples**: Added real book cover images (Elle en Eve, Tom/Isa/Phoebe, Mama Prinses)
- **Messaging Updates**: Removed "handmade" references, focused on capacity limitations
- **FAQ Expansion**: Added 11 new FAQ questions grouped into 4 categories (Algemene Informatie, Bestelling & Levering, Wijzigingen & Service, Speciale Gelegenheden)
- **Email Integration**: Updated waitlist button to link to hoi@stervanhetverhaal with proper subject line
- **Content Cleanup**: Removed "Bekijk enkele voorbeelden van onze mooie illustraties" text from examples section

### Future Expansion Possibilities
- **Backend Integration**: Could be extended with contact forms, booking systems
- **E-commerce**: Potential integration with payment processing
- **Content Management**: Could add CMS for dynamic content updates
- **Multi-language**: Structure supports internationalization